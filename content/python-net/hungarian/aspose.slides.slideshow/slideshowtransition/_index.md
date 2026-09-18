---
title: SlideShowTransition class
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition osztály

A diavetítés átmenetét képviseli.

A SlideShowTransition típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`sound`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound/) | Visszaadja vagy beállítja a beágyazott audio adatot.<br/>            Olvasás/írás [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Beállítja vagy visszaadja a hang módot a diavetítés átmenetéhez.<br/>            Olvasás/írás [`TransitionSoundMode`](/slides/python-net/hu/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Ez az attribútum megadja, hogy a hang addig ismétlődik-e, amíg a következő hangesemény a diavetítésben nem következik be.<br/>            Olvasás/írás **bool**. |
| [`advance_on_click`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Megadja, hogy egy egérkattintás előrehozza-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor igaz érték feltételezhető.<br/>            Olvasás/írás **bool**. |
| [`advance_after`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/advance_after/) | Ez az attribútum megadja, hogy a diavetítés egy bizonyos idő után a következő diára lép-e.<br/>            Olvasás/írás **bool**. |
| [`advance_after_time`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Megadja az időt, ezredmásodpercben, amafter a átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor azt feltételezzük, hogy nem lesz automatikus előrehaladás.<br/>            Olvasás/írás **int**. |
| [`speed`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/speed/) | Megadja az átmenet sebességét, amelyet az aktuális diáról a következőre történő átmenet során használnak.<br/>            Olvasás/írás [`TransitionSpeed`](/slides/python-net/hu/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/value/) | Diavetítés átmeneti érték.<br/>            Csak olvasás [`ITransitionValueBase`](/slides/python-net/hu/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/type/) | Az átmenet típusa.<br/>            Olvasás/írás [`TransitionType`](/slides/python-net/hu/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igazra van állítva, akkor a generáló alkalmazás értesül, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén egy egyéni nevet vagy felhasználói felületet jeleníthet meg.<br/>            Olvasás/írás **bool**. |
| [`sound_name`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound_name/) | Megad egy ember által olvasható nevet az átmenet hangjának. A [`SlideShowTransition.sound`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/sound) tulajdonságot kell beállítani a hangnév lekéréséhez vagy beállításához.<br/>            Olvasás/írás **str**. |
| [`duration`](/slides/python-net/hu/aspose.slides.slideshow/slideshowtransition/duration/) | Visszaadja vagy beállítja a diák átmeneti effektusának időtartamát ezredmásodpercben.<br/>            Olvasás/írás **int**. |

### Lásd még
* modul [`aspose.slides.slideshow`](/slides/python-net/hu/aspose.slides.slideshow)
* könyvtár [`Aspose.Slides`](/slides/python-net)