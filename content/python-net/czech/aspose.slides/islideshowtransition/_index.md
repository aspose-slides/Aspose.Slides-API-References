---
title: ISlideShowTransition class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/islideshowtransition/
---
## ISlideShowTransition třída

Reprezentuje přechod prezentace.

Typ ISlideShowTransition vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`sound`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound/) | Vrací nebo nastavuje vložená zvuková data.<br/>            Čtení/zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound_mode/) | Nastaví nebo vrátí režim zvuku pro přechod mezi snímky.<br/>            Čtení/zápis [`TransitionSoundMode`](/slides/python-net/cs/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound_loop/) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v<br/>            prezentaci.<br/>            Čtení/zápis **bool**. |
| [`advance_on_click`](/slides/python-net/cs/aspose.slides/islideshowtransition/advance_on_click/) | Určuje, zda kliknutí myší posune snímek dopředu, nebo ne. Pokud není tento atribut<br/>            specifikován, předpokládá se hodnota true.<br/>            Čtení/zápis **bool**. |
| [`advance_after`](/slides/python-net/cs/aspose.slides/islideshowtransition/advance_after/) | Tento atribut určuje, zda se prezentace po určité době přesune na další snímek.<br/>            Čtení/zápis **bool**. |
| [`advance_after_time`](/slides/python-net/cs/aspose.slides/islideshowtransition/advance_after_time/) | Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení<br/>            může být použito spolu s atributem advClick. Pokud není tento atribut<br/>            specifikován, předpokládá se, že nedojde k automatickému posunu.<br/>            Čtení/zápis **int**. |
| [`speed`](/slides/python-net/cs/aspose.slides/islideshowtransition/speed/) | Určuje rychlost přechodu, která se má použít při přechodu z aktuálního snímku<br/>            na další.<br/>            Čtení/zápis [`TransitionSpeed`](/slides/python-net/cs/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/cs/aspose.slides/islideshowtransition/value/) | Hodnota přechodu prezentace.<br/>            Pouze pro čtení [`ITransitionValueBase`](/slides/python-net/cs/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/cs/aspose.slides/islideshowtransition/type/) | Typ přechodu.<br/>            Čtení/zápis [`TransitionType`](/slides/python-net/cs/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound_is_built_in/) | Určuje, zda je tento zvuk vestavěný nebo ne. Pokud je tento atribut nastaven na true, pak<br/>            generující aplikace je upozorněna, aby zkontrolovala atribut name specifikovaný pro tento zvuk<br/>            v seznamu vestavěných zvuků a může následně zobrazit vlastní název nebo UI podle potřeby.<br/>            Čtení/zápis **bool**. |
| [`sound_name`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound_name/) | Určuje čitelný název zvuku přechodu. Vlastnost [`ISlideShowTransition.sound`](/slides/python-net/cs/aspose.slides/islideshowtransition/sound) musí být přiřazena pro získání nebo nastavení názvu zvuku.<br/>            Čtení/zápis **str**. |
| [`duration`](/slides/python-net/cs/aspose.slides/islideshowtransition/duration/) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách.<br/>            Čtení/zápis **int**. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)