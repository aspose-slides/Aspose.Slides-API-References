---
title: SlideShowTransition
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt DiashowÜbergänge dar.
type: docs
weight: 9570
url: /de/net/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition class

Stellt Diashow-Übergänge dar.

```csharp
public class SlideShowTransition : DomObject<BaseSlide>, ISlideShowTransition
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdvanceAfter](../../aspose.slides.slideshow/slideshowtransition/advanceafter) { get; set; } | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen/SchreibenBoolean . |
| [AdvanceAfterTime](../../aspose.slides.slideshow/slideshowtransition/advanceaftertime) { get; set; } | Gibt die Zeit in Millisekunden an, nach der der Übergang beginnen soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist , wird davon ausgegangen, dass kein automatischer Vorlauf erfolgt. Lesen/SchreibenUInt32 . |
| [AdvanceOnClick](../../aspose.slides.slideshow/slideshowtransition/advanceonclick) { get; set; } | Gibt an, ob ein Mausklick die Folie vorwärts bewegt oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von wahr angenommen. Lesen/SchreibenBoolean . |
| [Sound](../../aspose.slides.slideshow/slideshowtransition/sound) { get; set; } | Gibt die eingebetteten Audiodaten zurück oder legt sie fest. Lesen/Schreiben[`IAudio`](../../aspose.slides/iaudio) . |
| [SoundIsBuiltIn](../../aspose.slides.slideshow/slideshowtransition/soundisbuiltin) { get; set; } | Gibt an, ob dieser Sound ein eingebauter Sound ist oder nicht. Wenn dieses Attribut auf „true“ gesetzt ist, wird die generierende Anwendung darauf hingewiesen, das für diesen Sound in der Liste der integrierten Sounds angegebene Namensattribut zu überprüfen, und kann dann nach Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche anzeigen. Lesen/SchreibenBoolean . |
| [SoundLoop](../../aspose.slides.slideshow/slideshowtransition/soundloop) { get; set; } | Dieses Attribut gibt an, ob der Ton wiederholt wird, bis das nächste Tonereignis in Slideshow auftritt. Lesen/SchreibenBoolean . |
| [SoundMode](../../aspose.slides.slideshow/slideshowtransition/soundmode) { get; set; } | Legt den Tonmodus für den Folienübergang fest oder gibt ihn zurück. Lesen/Schreiben[`TransitionSoundMode`](../transitionsoundmode) . |
| [SoundName](../../aspose.slides.slideshow/slideshowtransition/soundname) { get; set; } | Gibt einen für Menschen lesbaren Namen für den Ton des Übergangs an. Das[`Sound`](./sound) Die Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder festzulegen. Lesen/SchreibenString . |
| [Speed](../../aspose.slides.slideshow/slideshowtransition/speed) { get; set; } | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Lesen/Schreiben[`TransitionSpeed`](../transitionspeed) . |
| [Type](../../aspose.slides.slideshow/slideshowtransition/type) { get; set; } | Art des Übergangs. Lesen/Schreiben[`TransitionType`](../transitiontype) . |
| [Value](../../aspose.slides.slideshow/slideshowtransition/value) { get; } | Diashow-Übergangswert. Schreibgeschützt[`ITransitionValueBase`](../itransitionvaluebase) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides.slideshow/slideshowtransition/equals)(object) | Bestimmt, ob die beiden SlideShowTransition-Instanzen gleich sind. Lesen/SchreibenBoolean . |
| override [GetHashCode](../../aspose.slides.slideshow/slideshowtransition/gethashcode)() | Dient als Hash-Funktion für einen bestimmten Typ, geeignet für die Verwendung in Hash-Algorithmen und Datenstrukturen wie einer Hash-Tabelle. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [BaseSlide](../../aspose.slides/baseslide)
* interface [ISlideShowTransition](../../aspose.slides/islideshowtransition)
* namensraum [Aspose.Slides.SlideShow](../../aspose.slides.slideshow)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->