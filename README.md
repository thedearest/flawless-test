### Flawless-test Task

#### Необходимые условия
1. Семантическая, валидная html 5 верстка.
2. При верстке нельзя использовать таблицы, фреймы, сторонние JS/CSS-библиотеки, кроме верстки слайдера. Для слайдера можно взять готовую js-библиотеку.
3. Серверную часть программировать не надо.
4. Попробуйте сделать адаптивную верстку на свое усмотрение, так как готового дизайна нет (минимум под телефон 320).
5. Макет должен быть доступным (hover, focus) и расширяемым (изменение текста не должно ломать верстку).
6. Слайдер сделать с тремя “слайдами” (с одинаковым дизайном, как на макете).

#### Technologies:

1. HTML
2. CSS (SCSS)
3. Vanilla JS
4. Carousel library (one script)
5. Gulp boilerplate by [ryanbenson](https://github.com/ryanbenson/Harvest)
6. Sprites
7. Responsive design
and more..

#### Validators and optimizing tools

-[validatorW3C](https://validator.w3.org/) - No errors. Warnings: Section lacks heading. Consider using h2-h6 elements (headings do exist, but in sections child elements).

-[googlePageInsight](https://developers.google.com/speed/pagespeed/insights/?url=actually-vase.surge.sh&tab=mobile) - Mobile 71/100, Desktop 91/100.

#### [Link](http://actually-vase.surge.sh/)

#### To run in prod. mode, clone repository, run `npm install/yarn` and, after installation, use `gulp`. To deploy, simply run `gulp deploy`.