---
title: ITextAnimation
second_title: Aspose.Slides voor Android via Java API-referentie
description: Tekstanimatie weergeven.
type: docs
url: /nl/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Tekstanimatie weergeven.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Voeg een nieuw effect toe aan het einde van de huidige reeks tot het einde van groeps-tekstanimaties. |
| [getBuildType()](#getBuildType--) | Lijst van build type (bijv. |
| [setBuildType(int value)](#setBuildType-int-) | Lijst van build type (bijv. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Gekoppeld vormeffect met groep of niet (null) Lezen/Schrijven [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Gekoppeld vormeffect met groep of niet (null) Lezen/Schrijven [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Voeg een nieuw effect toe aan het einde van de huidige reeks tot het einde van groeps-tekstanimaties. Alleen geldig als het aantal tekstelementen gelijk is aan of groter is dan het aantal effecten van deze groep!

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| effectType | int | Type van een animatie-effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtype van animatie-effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger-type van effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retourwaarde:**
[IEffect](../../com.aspose.slides/ieffect) - Nieuw effectobject [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Lijst van build type (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/Schrijven \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Retourwaarde:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Lijst van build type (bijv. Paragraaf 1,2,3, Alles tegelijk) van tekstanimatie. Lezen/Schrijven \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Gekoppeld vormeffect met groep of niet (null) Lezen/Schrijven [IEffect](../../com.aspose.slides/ieffect).

**Retourwaarde:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Gekoppeld vormeffect met groep of niet (null) Lezen/Schrijven [IEffect](../../com.aspose.slides/ieffect).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |