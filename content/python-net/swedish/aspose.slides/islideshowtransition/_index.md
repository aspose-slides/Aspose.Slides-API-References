---
title: ISlideShowTransition class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islideshowtransition/
---
## ISlideShowTransition klass

Representerar bildspelsövergång.

Typen ISlideShowTransition exponeras följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`sound`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound/) | Returnerar eller anger den inbäddade ljuddata.<br/>            Läs-skriv [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound_mode/) | Ställer in eller returnerar ljudläge för bildspelsövergång.<br/>            Läs-skriv [`TransitionSoundMode`](/slides/python-net/sv/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound_loop/) | Det här attributet anger om ljudet ska loopa tills nästa ljudevenemang inträffar i<br/>            bildspel.<br/>            Läs-skriv **bool**. |
| [`advance_on_click`](/slides/python-net/sv/aspose.slides/islideshowtransition/advance_on_click/) | Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte<br/>            anges antas ett värde av true.<br/>            Läs-skriv **bool**. |
| [`advance_after`](/slides/python-net/sv/aspose.slides/islideshowtransition/advance_after/) | Det här attributet anger om bildspelet ska gå till nästa bild efter en viss tid.<br/>            Läs-skriv **bool**. |
| [`advance_after_time`](/slides/python-net/sv/aspose.slides/islideshowtransition/advance_after_time/) | Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning<br/>            kan användas tillsammans med advClick-attributet. Om detta attribut inte anges<br/>            antas att ingen automatisk vidaregång sker.<br/>            Läs-skriv **int**. |
| [`speed`](/slides/python-net/sv/aspose.slides/islideshowtransition/speed/) | Anger övergångshastigheten som ska användas när man övergår från den aktuella bilden<br/>            till nästa.<br/>            Läs-skriv [`TransitionSpeed`](/slides/python-net/sv/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/sv/aspose.slides/islideshowtransition/value/) | Värde för bildspelsövergång.<br/>            Läs-endast [`ITransitionValueBase`](/slides/python-net/sv/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/sv/aspose.slides/islideshowtransition/type/) | Typ av övergång.<br/>            Läs-skriv [`TransitionType`](/slides/python-net/sv/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound_is_built_in/) | Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är satt till true så<br/>            meddelas den genererande applikationen att kontrollera name-attributet som specificerats för detta ljud<br/>            i dess lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov.<br/>            Läs-skriv **bool**. |
| [`sound_name`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound_name/) | Anger ett människoläsbart namn för övergångens ljud. [`ISlideShowTransition.sound`](/slides/python-net/sv/aspose.slides/islideshowtransition/sound)-egenskapen måste tilldelas för att hämta eller ange ljudnamnet.<br/>            Läs-skriv **str**. |
| [`duration`](/slides/python-net/sv/aspose.slides/islideshowtransition/duration/) | Hämtar eller anger varaktigheten för bildövergångseffekten i millisekunder.<br/>            Läs-skriv **int**. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)