---
title: TextAnimation
second_title: Aspose.Slides voor Java API-referentie
description: Stelt tekstanimatie voor.
type: docs
url: /nl/com.aspose.slides/textanimation/
---
**Inheritance:**  
Erfenis:

java.lang.Object

**All Implemented Interfaces:**  
Alle geïmplementeerde interfaces:

[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Represent text animation.  
Stelt tekstanimatie voor.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |

## Methods

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Voeg een nieuw effect toe aan het einde van de huidige reeks tekstanimaties van de groep. |
| [getBuildType()](#getBuildType--) | Lijst van bouwtype (bijv. |
| [setBuildType(int value)](#setBuildType-int-) | Lijst van bouwtype (bijv. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Gelinkte vormeffect met groep of niet (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Gelinkte vormeffect met groep of niet (null). |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Voeg een nieuw effect toe aan het einde van de huidige reeks tekstanimaties van de groep. Alleen geldig als het aantal tekstparagrafen gelijk is aan of groter is dan het aantal effecten van deze groep!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/schrijven [BuildType](../../com.aspose.slides/buildtype).

**Returns:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/schrijven [BuildType](../../com.aspose.slides/buildtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Gelinkte vormeffect met groep of niet (null). Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Returns:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Gelinkte vormeffect met groep of niet (null). Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |