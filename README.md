# EN - Engeto Academy - Project-1

Project #1 (HTML, CSS, JS) of Front-end Developer Academy at Engeto.cz

This is a solution for [Engeto Academy - Project 1](https://engeto.cz/webova-akademie/).

## Table of Contents

- ➡️[Description](#description)
- ➡️[Specifications](#specifications)
- ➡️[Screenshot](#screenshot)
- ➡️[Live Site](#live)
- ➡️[Media Queries](#media-queries)
- ➡️[Author](#author)
- ➡️[Codereview](#codereview)

## Description

This project was created as one of the three projects from the Engeto Academy - Front-end Developer course. The goal of this project is to faithfully imitate the visual design of a page titled "Your Travel Assistant." The main benefit of this project is to practice working with media queries, which are used to adjust various cascading styles of the page based on the size of the device on which they are displayed, especially mobile phones, tablets, laptops, and large monitors.

## Assignment

The task is to create a simple responsive web page. The page will adapt its layout according to the display width; in simpler terms, it will look different on mobile and desktop. Examples of the final display, including the assignment (images, icons, colors, etc.), can be found on Google Drive and Figma.

You will have time to complete the task until the end of the academy. Remember that there is no single correct solution, and most things can be solved in multiple ways.

The assignment can be found on Google Drive. This time, we intentionally do not provide detailed instructions so that you can reflect on the project and try to work on it independently. :) Regarding various distances (margin, padding), it is not necessary for everything to be exactly the same as in the assignment image. Nowadays, we don't aim for pixel perfection. :)

## Specifications

🟢 "Mobile-first" approach 📲 <br>
🟢 Semantic HTML5 markup<br>
🟢 Custom CSS properties<br>
🟢 Flexbox<br>
🟢 CSS Grid<br>
🟢 [Google Fonts](https://fonts.google.com/) - '<i>Poppins</i>', '<i>Montserrat</i>'<br>
🟢 [Remixicon](https://remixicon.com/) - Open-source icon system<br>
🟢 [ScrollReveal](https://scrollrevealjs.org/) - JS library for animations<br>
🟢 Sticky navigation menu (show/hide) - only for mobile devices<br>

## Screenshot

<img src="design/design-preview.jpg" alt="Engeto Project 1">

## Live Site

- Live Site URL: ➡️ [www.petrb-engeto-academy-1.netlify.app/](https://petrb-engeto-academy-1.netlify.app) ⬅️

### Media Queries

- small mobile: 0-340px
- mobile (default): 340-480px
- tablet: 480-490px, 490-768px
- laptop: 768px-1023px
- big screen: 1023px-1152px

## Author

- Website - [Petr Bednarski](https://github.com/pettik)
- Frontend Mentor - [@pettik](https://www.frontendmentor.io/profile/pettik)

## Codereview

Congratulations, great job! You successfully met our requirements, and your project has the status FULFILLED.

Tutor's feedback: **FULFILLED**

**What I liked:** I appreciate all the additional things you did in the project - favicon, working menu, JavaScript animations, gradual page loading, enabling live deployment, README.md, etc. In this feedback, I will comment only on things within the scope of the assignment - for other aspects, I will provide feedback on Discord. ;)

**Regarding the overall implementation:** the page looks clean, professional, and engaging for the visitor.

**Regarding the HTML code:** it is clean, clear, and easy to navigate, mainly due to comments and empty lines. It is also machine-readable because it includes semantic elements.

**Regarding the CSS code:** it is also clear, easy to navigate. You use the right properties and are not afraid to delve into slightly more complex things like transitions, transformations, blur, etc. I appreciate the use of variables for colors and other constant values.

**Areas for improvement:** The hero section (the first large image) should take up the entire screen (both width and height) - you can achieve this by adding the property `height: 100vh` (mainly, so you know about it ;)). In the CSS file, you use a lot of variables, but some colors stored in variables are missing - I recommend adding them. While it may not save much typing, it's good to have the entire color palette in one place - easy to change and provides a better overview. Also, considering that you store quite a few things, it might be worth considering whether to save the breakpoints for media query blocks as well. In the .nav class for min-width:1152px, you have incorrectly written the value of the width property - unfortunately, this won't work (height: calc(var--header-height) + 1.5rem;) - it should be height: calc(var(--header-height) + 1.5rem;).

**Conclusion:** Overall, the project looks very nice. You demonstrate that you understand all the concepts we require, and at the same time, you added many parts that are very interesting and beyond the requirements."

<hr>

# CZ - Engeto Academy - Projekt-1

Projekt č. 1 (HTML, CSS, JS) Front-end Developer Academy na Engeto.cz

Toto je řešení k [Engeto Academy - Projekt 1](https://engeto.cz/webova-akademie/).

## Obsah

- ➡️[Popis](#popis)
- ➡️[Specifikace](#specifikace)
- ➡️[Screenshot](#screenshot)
- ➡️[Živý web](#live)
- ➡️[Media Queries](#media-queries)
- ➡️[Autor](#autor)
- ➡️[Hodnocení](#autor)

## Popis

Tento projekt byl vytvořen jako jeden ze tří projektů z Engeto Academy - Kurzu Front-end Developer. Cílem tohoto projektu je co nejvěrněji imitovat vizuální design stránky s názvem "Your Travel Assistant." Hlavním přínosem tohoto projektu je procvičení práce s media queries, které jsou použity k úpravě různých kaskádových stylů stránky v závislosti na velikosti zařízení, na kterém jsou zobrazeny, zejména mobilní telefony, tablety, notebooky a velké monitory.

## Zadání

Úkolem bude vytvoření jednoduché responzivní webové stránky. Stránka se bude přizpůsobovat rozložením podle šířky displeje, zjednodušeně řečeno, jinak bude vypadat na mobilu a jinak na desktopu. Ukázky výsledného zobrazení včetně zadání (obrázky, ikony, barvy apod.) se nacházejí na Google Disku a Figme .

Na vypracování úkolu budeš mít čas do konce akademie. Pamatuj, že neexistuje jedno správné řešení a většina věcí se dá řešit více způsoby.

Zadání najdeš na Google Disku. Záměrně tentokrát neposkytujeme detailní návod, ať se můžeš nad projektem zamyslet a vyzkoušet si vše vypracovat samostatně. :) Co se týká různých vzdáleností (margin, padding), není nutné, aby bylo vše naprosto stejné jako na obrázku v zadání. V dnešní době už nekódujeme pixel perfect. :)

## Specifikace

🟢 "Mobile-first" přístup 📲 <br>
🟢 Sémantický značkovací jazyk HTML5<br>
🟢 Vlastní vlastnosti CSS<br>
🟢 Flexbox<br>
🟢 CSS Grid<br>
🟢 [Google Fonts](https://fonts.google.com/) - '<i>Poppins</i>', '<i>Montserrat</i>'<br>
🟢 [Remixicon](https://remixicon.com/) - Open-source systém ikon<br>
🟢 [ScrollReveal](https://scrollrevealjs.org/) - JS knihovna pro animace<br>
🟢 Lepící se navigační menu (zobrazení/skrytí) - pouze pro mobilní zařízení<br>

## Screenshot

<img src="design/design-preview.jpg" alt="Engeto Projekt 1">

## LIVE web

- URL živého webu: ➡️ [www. petrb-engeto-academy-1.netlify.app/](https://petrb-engeto-academy-1.netlify.app) ⬅️

### Media-queries

- malý mobil: 0-340px
- mobil (výchozí): 340-480px
- tablet: 480-490px, 490-768px
- notebook: 768px-1023px
- velká obrazovka: 1023px-1152px

## Autor

- Webová stránka - [Petr Bednarski](https://github.com/pettik)
- Frontend Mentor - [@pettik](https://www.frontendmentor.io/profile/pettik)

## Hodnocení Engeto lektora

Gratulujeme, skvělá práce! Povedlo se ti zvládnout naše požadavky a tvůj projekt má status SPLNĚNO.

Hodnocení od lektora: **SPLNĚNO**

**Co se mi líbilo:** Oceňuji všechny věci navíc, které jsi v projektu udělal - favicon, fungující menu, javascriptové animace, postupné načítání stránky, zprovoznění live spuštění, README.md atd. V tomto feedbacku ale budu komentovat jen věci v rozsahu zadání - na ostatní ti napíšu feedback na discord. ;)

**Co se týče celkového provedení:** stránka vypadá čistě, profesionálně, pro návštěvníka je zajímavá.

**Co se týče html kódu:** ten je čistý, přehledný, dá se v něm orientovat, v čemž pomáhají hlavně komentáře, prázdné řádky. Strojově je také dobře čitelný, protože obsahuje sémantické elementy.

**Co se týče css kódu:** také je přehledný, dá se v něm orientovat. Používáš správné vlastnosti, nebojíš se jít i do něčeho trochu složitějšího jako jsou přechody, transformace, blur atp. Oceňuji používání proměnných na barvy a další konstantní hodnoty.

**Co by jsi měl/a zlepšit:** Sekce hero (tzn. ten první velký obrázek) by měl zabírat celou obrazovku (na šířku i na výšku) - dosáhneš toho přidáním vlastnosti height: 100vh (hlavně, abys o ní věděl ;)).
V css souboru používáš hodně proměnných, stejně ale pak některé barvy uložené v proměnných nemáš - doporučuji si je tam přidat - i když si tím možná psaní moc neušetříš, tak je fajn mít celou barevnou paletu na jednom místě - snadno se to mění a obecně máš lepší přehled. Také (vzhledem k tomu, že si ukládáš docela dost věcí), tak by stálo za zvážení, jestli si neuložit i samotné breakpointy pro media query bloky.
Ve třídě .nav pro min-width:1152px máš špatně napsanou hodnotu vlastnosti width - takto to bohužel nefunguje (height: calc(var--header-height) + 1.5rem;) - správně je to height: calc(var(--header-height) + 1.5rem);

**Závěr**: Celkově je projekt moc hezký, ukazuješ, že umíš veškeré koncepty, které požadujeme a zároveň jsi tam přidal mnoho částí, které jsou velmi zajímavé a navíc.
