# Frontend 2 (@CMDA) classroom

<!--lint disable no-html-->

<!--lint enable maximum-line-length-->

## Table of Contents

* [Synopsis](#synopsis)
* [Description](#description)
* [Communication](#communication)
* [Goals](#goals)
* [Grade](#grade)
* [Calendar](#calendar)
* [Effort](#effort)
* [Materials](#materials)
* [Bugs](#bugs)
* [Programme](#programme)
* [Conduct](#conduct)
* [License](#license)

## Synopsis

The course **Frontend** is given at [**@CMDA**][cmda] in 2019 in the third en fourth quarter

* **Course**: Frontend 2
* **Coordinator**: Joost Faber
* **Lecturers**: Joost Faber, Casper Boutens
* **SIS**: Frontend Development 2
* **Credit**: 3 ECTS
* **Academic year**: 2018-2019
* **Period**: Quarter 3 & 4
* **Programme**: Communication and Multimedia Design (full time bachelor)
* **Language**: Dutch instructions and English resources
* **Entry requirements**: N/A

## Description

In Frontend 2 we concentrate on improving the knowledge of the core concepts of JavaScript and learn how to progressively enhance interfaces with HTML, CSS & JavaScript. In so called Dev-❤️-Des sessions multiple frontend components are designed and build.

Frontend 2 is an elective course given in Quarter 3 & 4 after the core curriculum of our programme, building further on knowledge acquired in Internetstandaarden, Inleiding Programmeren, and Frontend 1. This course is chosen alongside Backend and Project Tech, together making up Block Tech. In Project Tech you’ll apply your newfound frontend skills.

If you’d like to continue with web development after this course, do a tech internship next quarter (Q4), choose Information Design (includes Frontend Apps, Functional Programming, and Frontend Data) for the fall semester next year, and pick Minor Everything Web in the spring semester after that.

## Communication

* [GitHub][gh-fe] — Main source of information, assignments, important dates, and more
* [Slack][slack] — General chatter and Q&A
* [Moodle][moodle-fe] — Schedulers

## Goals

#### Main goals

The tow main goals in this course are that you:

* improve your knowledge about core JavaScript concepts
* are able build progressively enhanced frontend components

## Grade

| Task                               |   Weight |
| ---------------------------------- | -------: |
| [Participation][]                  |      10% |
| [Assessment 1※][a1] (digital test) |      40% |
| [Assessment 2※][a2] (oral test)    |      50% |
| **Total**                          | **100%** |

> ※ passing both tests (min 5.5) is required

```js
if (!participation && !a1 && !a2) {
  grade = 'GR';
} else if (a1 < 5.5 || a2 < 5.5) {
  grade = 1;
} else {
  grade = participation * 0.1 + a1 * 0.4 + a2 * 0.5;
}
```

## Calendar

## Effort

###### Per activity

###### Per week |

## Materials

#### Resources used in this course

#### Resources to refresh your memory

#### Resources used in previous courses

#### Resources used in Frontend 2

## Bugs

If you have questions:

* Read the manual for the technology in question
  ([Git](https://git-scm.com/docs),
  [GitHub](https://guides.github.com),
  [Node](https://nodejs.org/api/),
  [npm](https://docs.npmjs.com),
  [express](http://expressjs.com/en/4x/api.html),
  [MySQL](https://dev.mysql.com/doc/refman/5.7/en/),
  [MongoDB](https://docs.mongodb.com))
* [Browse examples][examples]
* [Search StackOverflow][stackoverflow]
* [Use a search engine like DuckDuckGo][duckduckgo]
* [Ask questions on Slack][slack]
* [Contact a lecturer][synopsis]

## Programme

This course is given at [Communication and Multimedia Design][bachelor], a
design bachelor focused on interactive digital products and services. CMD is
part of the [Faculty of Digital Media and Creative Industries][faculty] at the
[Amsterdam University of Applied Sciences][university].

[![][cmd-logo]][bachelor]

## Conduct

This course has a [Code of Conduct][coc]. Anyone interacting with this
repository, organisation, or community is bound by it.

Staff and students of the Amsterdam University of Applied Sciences (Hogeschool
van Amsterdam) are additionally bound by the [Regulation Undesirable
Conduct][ruc] ([Regeling Ongewenst Gedrag][rog]).

## License

Unless stated otherwise, code is [MIT][] © [Titus Wormer][author],
docs and images are [CC-BY-4.0][].

[mit]: license.md#code
[cc-by-4.0]: license.md#documentation-and-images
[cmda]: https://github.com/cmda
[fe3]: https://github.com/cmda-fe3/course-17-18
[gh-fe]: https://github.com/cmda-fe/course-1819
[slack]: https://cmda-tech.slack.com
[moodle-fe]: https://moodle.cmd.hva.nl/course/view.php?id=451
[rooster]: https://rooster.hva.nl
[http]: https://tools.ietf.org/html/rfc2068
[command-line]: https://en.wikipedia.org/wiki/Command-line_interface
[git]: https://git-scm.com
[stackoverflow]: https://stackoverflow.com
[duckduckgo]: https://duckduckgo.com
[synopsis]: #synopsis
[minor]: https://cmda.github.io/minor-everything-web/
[html-css]: https://learn.shayhowe.com/html-css/
[safari]: http://rps.hva.nl:2048/login?url=http://proquest.safaribooksonline.com/?uicode=hva
[lynda-portal]: https://lyndaportal.ict.hva.nl
[ydkjs-1]: https://github.com/getify/You-Dont-Know-JS/blob/master/up%20&%20going/README.md#you-dont-know-js-up--going
[ydkjs-2]: https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20&%20closures/README.md#you-dont-know-js-scope--closures
[ydkjs-3]: https://github.com/getify/You-Dont-Know-JS/blob/master/this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes
[ydkjs-4]: https://github.com/getify/You-Dont-Know-JS/blob/master/types%20&%20grammar/README.md#you-dont-know-js-types--grammar
[ydkjs-5]: https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/README.md#you-dont-know-js-async--performance
[ydkjs-6]: https://github.com/getify/You-Dont-Know-JS/blob/master/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond
[bachelor]: https://www.cmd-amsterdam.nl/english/
[faculty]: https://www.amsterdamuas.com/faculty/fdmci/faculty-of-digital-media-and-creative-industries.html
[university]: https://www.amsterdamuas.com
[cmd-logo]: images/cmd.jpg
[coc]: code-of-conduct.md
[ruc]: https://www.amsterdamuas.com/practical-matters/algemeen/hva-breed/juridische-zaken/legal-affairs/regulation-undesirable-conduct/regulation-undesirable-conduct.html#anker-3-complaints-authority
[rog]: https://www.hva.nl/praktisch/algemeen/hva-breed/juridische-zaken/loket-beroep-bezwaar-en-klacht/regeling-ongewenst-gedrag/regeling-ongewenst-gedrag.html?origin=gbS4rg%2FDTZuxQ6lGVF%2BN1A
[a1]: assessment-1.md
[a2]: assessment-2.md
[participation]: participation.md
[w1]: week-1.md
[w2]: week-2.md
[w3]: week-3.md
[w4]: week-4.md
[w5]: week-5.md
[w6]: week-6.md
[w1lec]: week-1.md#lecture
[w2lec]: week-2.md#lecture
[w3lec]: week-3.md#lecture
[w4lec]: week-4.md#lecture
[w5lec]: week-5.md#lecture
[w6lec]: week-6.md#lecture
[w1lab]: week-1.md#lab
[w2lab]: week-2.md#lab
[w3lab]: week-3.md#lab
[w4lab]: week-4.md#lab
[w5lab]: week-5.md#lab
[w6lab]: week-6.md#lab
[w7lab]: week-7.md#lab
[w8lab]: week-8.md#lab
[w1a]: week-1.md#assignments
[w2a]: week-2.md#assignments
[w3a]: week-3.md#assignments
[w4a]: week-4.md#assignments
[w5a]: week-5.md#assignments
