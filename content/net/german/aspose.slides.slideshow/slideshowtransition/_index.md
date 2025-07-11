---
title: SlideShowTransition
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt die Folienübergänge dar.
type: docs
weight: 10010
url: /de/aspose.slides.slideshow/slideshowtransition/
---

## SlideShowTransition-Klasse

Stellt die Folienübergänge dar.

```csharp
public class SlideShowTransition : DomObject<BaseSlide>, ISlideShowTransition
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdvanceAfter](../../aspose.slides.slideshow/slideshowtransition/advanceafter) { get; set; } | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechseln soll. Lese-/Schreib-Boolean. |
| [AdvanceAfterTime](../../aspose.slides.slideshow/slideshowtransition/advanceaftertime) { get; set; } | Gibt die Zeit in Millisekunden an, nach der der Übergang beginnen soll. Diese Einstellung kann in Verbindung mit dem Attribut advClick verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird davon ausgegangen, dass keine automatische Vorwärtsbewegung erfolgt. Lese-/Schreib-UInt32. |
| [AdvanceOnClick](../../aspose.slides.slideshow/slideshowtransition/advanceonclick) { get; set; } | Gibt an, ob ein Mausklick die Folie voranbringen wird oder nicht. Wenn dieses Attribut nicht angegeben ist, wird von einem Wert von true ausgegangen. Lese-/Schreib-Boolean. |
| [Sound](../../aspose.slides.slideshow/slideshowtransition/sound) { get; set; } | Gibt die eingebetteten Audiodaten zurück oder setzt sie. Lese-/Schreib-[`IAudio`](../../aspose.slides/iaudio). |
| [SoundIsBuiltIn](../../aspose.slides.slideshow/slideshowtransition/soundisbuiltin) { get; set; } | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die generierende Anwendung benachrichtigt, den für diesen Sound angegebenen Namen in ihrer Liste integrierter Sounds zu überprüfen und kann dann nach Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen. Lese-/Schreib-Boolean. |
| [SoundLoop](../../aspose.slides.slideshow/slideshowtransition/soundloop) { get; set; } | Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Soundereignis in der Diashow auftritt. Lese-/Schreib-Boolean. |
| [SoundMode](../../aspose.slides.slideshow/slideshowtransition/soundmode) { get; set; } | Gibt den Soundmodus für den Folienübergang an oder gibt ihn zurück. Lese-/Schreib-[`TransitionSoundMode`](../transitionsoundmode). |
| [SoundName](../../aspose.slides.slideshow/slideshowtransition/soundname) { get; set; } | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Die Eigenschaft [`Sound`](./sound) muss zugewiesen werden, um den Soundnamen zu erhalten oder festzulegen. Lese-/Schreib-String. |
| [Speed](../../aspose.slides.slideshow/slideshowtransition/speed) { get; set; } | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Lese-/Schreib-[`TransitionSpeed`](../transitionspeed). |
| [Type](../../aspose.slides.slideshow/slideshowtransition/type) { get; set; } | Art des Übergangs. Lese-/Schreib-[`TransitionType`](../transitiontype). |
| [Value](../../aspose.slides.slideshow/slideshowtransition/value) { get; } | Wert des Folienübergangs. Nur-Lese-[`ITransitionValueBase`](../itransitionvaluebase). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides.slideshow/slideshowtransition/equals)(object) | Bestimmt, ob die beiden SlideShowTransition-Instanzen gleich sind. Lese-/Schreib-Boolean. |
| override [GetHashCode](../../aspose.slides.slideshow/slideshowtransition/gethashcode)() | Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hashalgorithmen und Datenstrukturen wie einer Hashtabelle. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* Klasse [BaseSlide](../../aspose.slides/baseslide)
* Schnittstelle [ISlideShowTransition](../../aspose.slides/islideshowtransition)
* Namensraum [Aspose.Slides.SlideShow](../../aspose.slides.slideshow)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->