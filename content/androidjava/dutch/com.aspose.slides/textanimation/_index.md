---
title: TextAnimation
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt tekstananimatie.
type: docs
url: /nl/com.aspose.slides/textanimation/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Vertegenwoordigt tekstananimatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Voeg een nieuw effect toe aan het einde van de huidige reeks van groeps-tekstanimaties. |
| [getBuildType()](#getBuildType--) | Lijst van bouwtype (bijv. |
| [setBuildType(int value)](#setBuildType-int-) | Lijst van bouwtype (bijv. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Gelinkt vorm-effect met groep of niet (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Gelinkt vorm-effect met groep of niet (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Voeg een nieuw effect toe aan het einde van de huidige reeks van groeps-tekstanimaties. Alleen geldig als het aantal tekstrapparagrafen gelijk is aan of groter is dan het aantal effecten van deze groep!

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourwaarden:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effect-object [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles in één keer) van tekstananimatie. Lezen/schrijven [BuildType](../../com.aspose.slides/buildtype).

**Retourwaarden:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles in één keer) van tekstananimatie. Lezen/schrijven [BuildType](../../com.aspose.slides/buildtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Gelinkt vorm-effect met groep of niet (null). Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Retourwaarden:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Gelinkt vorm-effect met groep of niet (null). Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |