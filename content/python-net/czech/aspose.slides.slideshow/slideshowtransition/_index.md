---
title: SlideShowTransition class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition třída

Reprezentuje přechod prezentace.

Typ SlideShowTransition obsahuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound/) | Vrací nebo nastavuje vložená zvuková data.<br/>            Čtení/Zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Nastavuje nebo vrací režim zvuku pro přechod snímku.<br/>            Čtení/Zápis [`TransitionSoundMode`](/slides/python-net/cs/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v<br/>            prezentaci.<br/>            Čtení/Zápis **bool**. |
| [`advance_on_click`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Určuje, zda kliknutí myší přejde na další snímek nebo ne. Pokud není tento atribut<br/>            zadán, předpokládá se hodnota true.<br/>            Čtení/Zápis **bool**. |
| [`advance_after`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/advance_after/) | Tento atribut určuje, zda se prezentace přesune na další snímek po uplynutí určitého času.<br/>            Čtení/Zápis **bool**. |
| [`advance_after_time`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Určuje čas v milisekundách, po kterém má začít přechod. Toto nastavení<br/>            může být použito spolu s atributem advClick. Pokud není tento atribut zadán,<br/>            předpokládá se, že nedojde k automatickému posunu.<br/>            Čtení/Zápis **int**. |
| [`speed`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/speed/) | Určuje rychlost přechodu, která se použije při přechodu ze současného snímku<br/>            na další.<br/>            Čtení/Zápis [`TransitionSpeed`](/slides/python-net/cs/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/value/) | Hodnota přechodu prezentace.<br/>            Pouze pro čtení [`ITransitionValueBase`](/slides/python-net/cs/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/type/) | Typ přechodu.<br/>            Čtení/Zápis [`TransitionType`](/slides/python-net/cs/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Určuje, zda je tento zvuk vestavěný nebo ne. Pokud je tento atribut nastaven na true,<br/>            generující aplikace je upozorněna, aby zkontrolovala atribut name zadaný pro tento zvuk<br/>            v jejím seznamu vestavěných zvuků a může poté zobrazit vlastní název nebo uživatelské rozhraní podle potřeby.<br/>            Čtení/Zápis **bool**. |
| [`sound_name`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound_name/) | Určuje čitelné jméno zvuku přechodu. Vlastnost [`SlideShowTransition.sound`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/sound) musí být přiřazena pro získání nebo nastavení názvu zvuku.<br/>            Čtení/Zápis **str**. |
| [`duration`](/slides/python-net/cs/aspose.slides.slideshow/slideshowtransition/duration/) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách.<br/>            Čtení/Zápis **int**. |

### Viz také
* modul [`aspose.slides.slideshow`](/slides/python-net/cs/aspose.slides.slideshow)
* knihovna [`Aspose.Slides`](/slides/python-net)