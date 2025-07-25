---
title: IEffect
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Animationseffekt dar.
type: docs
weight: 410
url: /de/aspose.slides.animation/ieffect/
---

## IEffect-Schnittstelle

Stellt einen Animationseffekt dar.

```csharp
public interface IEffect
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AfterAnimationColor](../../aspose.slides.animation/ieffect/afteranimationcolor) { get; set; } | Definiert eine Nachanimationsfarbe für den Effekt. Lesen/Speichern [`IColorFormat`](../../aspose.slides/icolorformat). |
| [AfterAnimationType](../../aspose.slides.animation/ieffect/afteranimationtype) { get; set; } | Definiert einen Nachanimationstyp für den Effekt. Lesen/Speichern [`AfterAnimationType`](./afteranimationtype). |
| [AnimateTextType](../../aspose.slides.animation/ieffect/animatetexttype) { get; set; } | Definiert einen Animationstexttyp für den Effekt. Der Text der Form kann zeichenweise, wortweise oder alles auf einmal animiert werden. Lesen/Speichern [`AnimateTextType`](./animatetexttype). |
| [Behaviors](../../aspose.slides.animation/ieffect/behaviors) { get; set; } | Gibt eine Sammlung von Verhalten für den Effekt zurück. Lesen/Speichern [`IBehaviorCollection`](../ibehaviorcollection). |
| [DelayBetweenTextParts](../../aspose.slides.animation/ieffect/delaybetweentextparts) { get; set; } | Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Wirkungsdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lesen/Speichern Single. |
| [PresetClassType](../../aspose.slides.animation/ieffect/presetclasstype) { get; set; } | Definiert die Klasse des Effekts. Lesen/Speichern [`EffectPresetClassType`](../effectpresetclasstype). |
| [Sequence](../../aspose.slides.animation/ieffect/sequence) { get; } | Gibt eine Sequenz für einen Effekt zurück. Nur lesen [`ISequence`](../isequence). |
| [Sound](../../aspose.slides.animation/ieffect/sound) { get; set; } | Definiert den eingebetteten Klang für den Effekt. Lesen/Speichern [`IAudio`](../../aspose.slides/iaudio). |
| [StopPreviousSound](../../aspose.slides.animation/ieffect/stopprevioussound) { get; set; } | Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Klang stoppt. Lesen/Speichern Boolean. |
| [Subtype](../../aspose.slides.animation/ieffect/subtype) { get; set; } | Definiert den Subtyp des Effekts. Lesen/Speichern [`EffectSubtype`](../effectsubtype). |
| [TargetShape](../../aspose.slides.animation/ieffect/targetshape) { get; } | Gibt die Zielform für den Effekt zurück. Nur lesen [`IShape`](../../aspose.slides/ishape). |
| [TextAnimation](../../aspose.slides.animation/ieffect/textanimation) { get; } | Gibt die Textanimation zurück. Nur lesen [`ITextAnimation`](../itextanimation). |
| [Timing](../../aspose.slides.animation/ieffect/timing) { get; set; } | Definiert den Timing-Wert für den Effekt. Lesen/Speichern [`ITiming`](../itiming). |
| [Type](../../aspose.slides.animation/ieffect/type) { get; set; } | Definiert den Typ des Effekts. Lesen/Speichern [`EffectType`](../effecttype). |

### Siehe auch

* Namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->