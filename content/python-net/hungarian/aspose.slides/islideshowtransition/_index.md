---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/islideshowtransition/
---
## ISlideShowTransition class

A diavetítés átmenetet képviseli.

Az ISlideShowTransition típus a következő tagokat teszi közzé:

## Properties

| Tulajdonság | Leírás |
| :- | :- |
| [`sound`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound/) | Visszaadja vagy beállítja a beágyazott audio adatot.<br/>            Read-write [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound_mode/) | Beállítja vagy visszaadja a hangmódot a diavetítés átmenethez.<br/>            Read-write [`TransitionSoundMode`](/slides/python-net/hu/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound_loop/) | Ez az attribútum azt határozza meg, hogy a hang addig ismétlődjön, amíg a következő hangesemény nem fordul elő a diavetítésben.<br/>            Read-write **bool**. |
| [`advance_on_click`](/slides/python-net/hu/aspose.slides/islideshowtransition/advance_on_click/) | Megadja, hogy az egérkattintás előreviszi-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor a true érték feltételezett.<br/>            Read-write **bool**. |
| [`advance_after`](/slides/python-net/hu/aspose.slides/islideshowtransition/advance_after/) | Ez az attribútum azt határozza meg, hogy a diavetítés egy bizonyos idő után továbblép-e a következő diára.<br/>            Read/write **bool**. |
| [`advance_after_time`](/slides/python-net/hu/aspose.slides/islideshowtransition/advance_after_time/) | Megadja azt az időt (milliszekundumban), amely után az átmenetnek el kell indulnia. Ez a beállítás használható az advClick attribútummal együtt. Ha ez az attribútum nincs megadva, akkor feltételezhető, hogy nem történik automatikus előrehaladás.<br/>            Read-write **int**. |
| [`speed`](/slides/python-net/hu/aspose.slides/islideshowtransition/speed/) | Megadja az átmenet sebességét, amely az aktuális diáról a következőre történő átmenet során használatos.<br/>            Read-write [`TransitionSpeed`](/slides/python-net/hu/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/hu/aspose.slides/islideshowtransition/value/) | Diavetítés átmeneti érték.<br/>            Read-only [`ITransitionValueBase`](/slides/python-net/hu/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/hu/aspose.slides/islideshowtransition/type/) | Az átmenet típusa.<br/>            Read-write [`TransitionType`](/slides/python-net/hu/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound_is_built_in/) | Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum true-ra van állítva, akkor a generáló alkalmazás értesítést kap, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén egy egyedi nevet vagy felhasználói felületet jeleníthet meg.<br/>            Read-write **bool**. |
| [`sound_name`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound_name/) | Megad egy ember által olvasható nevet az átmenet hangjának. A [`ISlideShowTransition.sound`](/slides/python-net/hu/aspose.slides/islideshowtransition/sound) tulajdonságot kell beállítani a hangnév lekéréséhez vagy módosításához.<br/>            Read-write **str**. |
| [`duration`](/slides/python-net/hu/aspose.slides/islideshowtransition/duration/) | Lekéri vagy beállítja a diák átmeneti effektusának időtartamát milliszekundumban.<br/>            Read/write **int**. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)