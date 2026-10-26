---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Stelt tekstanimatie voor.
type: docs
url: /nl/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Stelt tekstanimatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Voeg een nieuw effect toe aan het einde van de huidige reeks tot het einde van de groep tekstanimaties. |
| [getBuildType()](#getBuildType--) | Lijst van bouwtype (bijv. |
| [setBuildType(int value)](#setBuildType-int-) | Lijst van bouwtype (bijv. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Gelinkt vormeffect met groep of niet (null) Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Gelinkt vormeffect met groep of niet (null) Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Voeg een nieuw effect toe aan het einde van de huidige reeks tot het einde van de groep tekstanimaties. Alleen geldig als het aantal tekstparagrafen gelijk is aan of groter is dan het aantal effecten van deze groep!

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Triggertype van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/schrijven \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Retour:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Lijst van bouwtype (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/schrijven \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Gelinkt vormeffect met groep of niet (null) Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Retour:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Gelinkt vormeffect met groep of niet (null) Lezen/schrijven [IEffect](../../com.aspose.slides/ieffect).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |