# commands

Post a new blog:
```
  hexo new post "title"
```

Generates public static files:
```
hexo generate OR hexo g
```

Start local server:
```
hexo server OR hexo s
```

Clean files
```
hexo clean OR hexo cl
```

One-stop deploy tools:
```
npm install hexo-deployer-git --save
```

Deploy:
```
cd blog
hexo clean OR hexo cl
hexo generate OR hexo g
hexo deploy OR hexo d
```


Problem fixes:


1. extends includes/layout.pug block content include..
```
npm install hexo-renderer-pug hexo-renderer-stylus --save
```
