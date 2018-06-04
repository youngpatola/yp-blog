+++
date = "2018-06-04T20:29:54+08:00"
title = "How I did it"

+++
Doing the obligatory but casual _How I created this blog using Hugo, Github, Netlify, and Forestry.io._ 

Requirements - Must have an account on Github, Netlify, and Forestry.io. You can just create a Github account since it can also be used to sign up on the latter websites. It's what I did.

Steps:

1. Firstly I installed Hugo through command line (what else). Referred to the [get started](https://gohugo.io/getting-started/) section of their docs.
2. Then I put  `netlify.toml` in my hugo directory and put this in:

   `\[context.production.environment\]`

   `  HUGO_VERSION = "0.26"`

   where  0.26 is my Hugo version. _If someone's following make sure you know what Hugo version you are running._
3. After setting up the theme and some sample posts it was time to push to the repo on the Github.
4. Logged in to Netlify and added my repo. Referred to the Hugo docs again regarding Netlify. The build command is hugo and the publish is public. Clicked some buttons and started the deploy. And then I made sure that my url is not bear-clear-butt.netlify.com. Went ahead and changed it while Netlify processes the deploy.
5. The blog was pretty much done, write some posts locally, push to Github via command line, and then Netlify checks and updates the changes. But accessing the command line was tiring so I signed up to Forestry.io.
6. Signed up to Forestry.io using Github. Connected my blog repo and waited for it to commit some files. You're already done when you can see your posts on the page.

# 🧀