---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje textovou animaci.
type: docs
url: /cs/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Reprezentuje textovou animaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. |
| [getBuildType()](#getBuildType--) | Seznam typu sestavení (např. |
| [setBuildType(int value)](#setBuildType-int-) | Seznam typu sestavení (např. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Propojený tvarový efekt se skupinou či nikoli (null) Číst/zapisovat [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Propojený tvarový efekt se skupinou či nikoli (null) Číst/zapisovat [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. Platí pouze, pokud počet textových odstavců je roven nebo větší než počet efektů v této skupině!

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect) - Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Seznam typu sestavení (např. Paragraph 1,2,3, All at Once) textové animace. Číst/zapisovat \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Návratová hodnota:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Seznam typu sestavení (např. Paragraph 1,2,3, All at Once) textové animace. Číst/zapisovat \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Propojený tvarový efekt se skupinou či nikoli (null) Číst/zapisovat [IEffect](../../com.aspose.slides/ieffect).

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Propojený tvarový efekt se skupinou či nikoli (null) Číst/zapisovat [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |