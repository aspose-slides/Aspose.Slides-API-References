---
title: ISlideShowTransition class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islideshowtransition/
---
## ISlideShowTransition Klasse

Represents slide show transition.

The ISlideShowTransition type exposes the following members:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`sound`](/slides/python-net/de/aspose.slides/islideshowtransition/sound/) | Gibt die eingebetteten Audiodaten zurück oder setzt sie.<br/>            Lesen/Schreiben [`IAudio`](/slides/python-net/de/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/de/aspose.slides/islideshowtransition/sound_mode/) | Setzt oder gibt den Soundmodus für die Folienübergabe zurück.<br/>            Lesen/Schreiben [`TransitionSoundMode`](/slides/python-net/de/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/de/aspose.slides/islideshowtransition/sound_loop/) | Dieses Attribut gibt an, ob der Sound in der Präsentation wiederholt wird, bis das nächste Sound-Ereignis eintritt.<br/>            Lesen/Schreiben **bool**. |
| [`advance_on_click`](/slides/python-net/de/aspose.slides/islideshowtransition/advance_on_click/) | Gibt an, ob ein Mausklick die Folie vorwärts schaltet oder nicht. Wenn dieses Attribut nicht<br/>            angegeben wird, wird ein Wert von true angenommen.<br/>            Lesen/Schreiben **bool**. |
| [`advance_after`](/slides/python-net/de/aspose.slides/islideshowtransition/advance_after/) | Dieses Attribut gibt an, ob die Präsentation nach einer bestimmten Zeit zur nächsten Folie wechselt.<br/>            Lesen/Schreiben **bool**. |
| [`advance_after_time`](/slides/python-net/de/aspose.slides/islideshowtransition/advance_after_time/) | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung<br/>            kann zusammen mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben<br/>            wird, wird angenommen, dass kein automatisches Vorwärtsblättern erfolgt.<br/>            Lesen/Schreiben **int**. |
| [`speed`](/slides/python-net/de/aspose.slides/islideshowtransition/speed/) | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie<br/>            zur nächsten verwendet werden soll.<br/>            Lesen/Schreiben [`TransitionSpeed`](/slides/python-net/de/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/de/aspose.slides/islideshowtransition/value/) | Wert des Präsentationsübergangs.<br/>            Nur lesend [`ITransitionValueBase`](/slides/python-net/de/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/de/aspose.slides/islideshowtransition/type/) | Typ des Übergangs.<br/>            Lesen/Schreiben [`TransitionType`](/slides/python-net/de/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/de/aspose.slides/islideshowtransition/sound_is_built_in/) | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das Namens-Attribut dieses Sounds in ihrer Liste integrierter Sounds zu prüfen und kann dann bei Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen.<br/>            Lesen/Schreiben **bool**. |
| [`sound_name`](/slides/python-net/de/aspose.slides/islideshowtransition/sound_name/) | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Die [`ISlideShowTransition.sound`](/slides/python-net/de/aspose.slides/islideshowtransition/sound) Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder zu setzen.<br/>            Lesen/Schreiben **str**. |
| [`duration`](/slides/python-net/de/aspose.slides/islideshowtransition/duration/) | Liefert oder setzt die Dauer des Folienübergangseffekts in Millisekunden.<br/>            Lesen/Schreiben **int**. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)