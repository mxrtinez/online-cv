![GitHub CI](https://github.com/mxrtinez/mxrtinez.github.io/actions/workflows/jekyll-gh-pages.yml/badge.svg)

# mxrtinez CV

Checkout the live demo [here](https://mxrtinez.github.io/).

## Installation

* [Fork](https://github.com/sharu725/online-cv/fork) the repository;
* Go to settings and set master branch as Github Pages source;
* Your new site should be ready at `https://<username>.github.io/online-cv/`;
* Printable version of the site can be found at `https://<username>.github.io/online-cv/print`. Use a third party link https://pdflayer.com/, https://www.web2pdfconvert.com/ etc to get the printable PDF.

Change all the details from one place: `_data/data.yml`.

### To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under <http://localhost:4000>.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 

```bash
git clone https://github.com/sharu725/online-cv.git
```

* Install required ruby gems

```bash
bundle install
```

* Serve the site locally

```bash
bundle exec jekyll serve
```

* Navigate to `http://localhost:4000`


## Skins

There are 6 color schemes available:

| Blue | Turquoise | Green |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/blue.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/turquoise.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/green.jpg" width="300"/> |

| Berry | Orange | Ceramic |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/berry.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/orange.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/ceramic.jpg" width="300"/> |

## Credits

Thanks to [Nelson Estevão](https://github.com/nelsonmestevao) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=nelsonmestevao).

Thanks to [t-h-e(sfrost)](https://github.com/t-h-e) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=t-h-e).

Check out for more themes: [**Jekyll Themes**](http://jekyll-themes.com).

> This theme is designed by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/).
> Visit [her website](http://themes.3rdwavemedia.com/) for more themes.
