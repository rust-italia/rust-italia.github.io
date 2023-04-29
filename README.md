# rust-italia.github.io

## Development

Clone the repository

With version 1.6.5 of Git and later (-j flag only available in version 2.8+):

```sh
git clone --recursive -j8 https://github.com/rust-italia/rust-italia.github.io.git
cd rust-italia.github.io.git
```

Install [zola](https://www.getzola.org/documentation/getting-started/installation/)

Start a local webserver:

```sh
zola serve
```

## Deploy

Just push to main. A GitHub action will take care of the deploy process.
