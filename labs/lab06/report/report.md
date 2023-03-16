---
## Front matter
title: "Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов"
subtitle: ""
author: "Симко Сергей Евгеньевич."

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

![](image/img1.png){#fig:001 width=70%}
![](image/img2.png){#fig:002 width=70%}
![](image/img3.png){#fig:003 width=70%}
![](image/img4.png){#fig:004 width=70%}
![](image/img5.png){#fig:005 width=70%}
![](image/img6.png){#fig:006 width=70%}
![](image/img7.png){#fig:007 width=70%}
![](image/img8.png){#fig:008 width=70%}
![](image/img9.png){#fig:009 width=70%}
![](image/img10.png){#fig:010 width=70%}


# Контрольные вопросы.

1. stdin, stdout, stderr
2. 

# Выводы

Я ознакомился с инструментами поиска файлов и фильтрации текстовых данных, приобрел навыки управления процессами и проверки использования диска и обслуживанию файловых систем.
