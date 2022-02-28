# Tailwind 3 Starter Kit

A template repo that works with TailwindCSS 3's JIT Engine and Hugo SSG. [Original by Praveen Juge](https://praveenjuge.com/blog/use-tailwind-jit-with-hugo/).

I forked and modified this repo to be a customized boilerplate. As such it has some commonly used template pieces as well as short codes. I also partialized the `<head>` tag and added my things such as [Fathom Analytics (Affiliate Link)](https://usefathom.com/ref/JHDRUD) and [FontAwesome](https://www.fontawesome.com). Other changes include installing every plugin. There is no reason not to install every plugin, since, at build, you will only generate the necessary CSS. 

The following instructions will get you going - if you're on windows, make sure you run them in bash:

## Install Dependencies

```sh
npm install
```

## Development Server

Tailwind Watcher:

```sh
npm run dev
```

Hugo Server, in another tab:

```sh
hugo server
```

## Production Build

```sh
npm run build && hugo --minify
```
