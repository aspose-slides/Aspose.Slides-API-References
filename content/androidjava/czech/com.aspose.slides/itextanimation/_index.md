---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /cs/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Represent text animation.
## Metody

| Metoda | Popis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. |
| [getBuildType()](#getBuildType--) | Seznam typů sestavení (např. |
| [setBuildType(int value)](#setBuildType-int-) | Seznam typů sestavení (např. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Propojený efekt tvaru se skupinou nebo ne (null) Číst/Zapisovat [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Propojený efekt tvaru se skupinou nebo ne (null) Číst/Zapisovat [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. Platí pouze, pokud počet textových odstavců je roven nebo větší než počet efektů této skupiny!

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| effectType | int | Typ animačního efektu [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy animačního efektu [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ spouštěče efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect) – Nový objekt efektu [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Seznam typů sestavení (např. odstavce 1,2,3, Vše najednou) textové animace. Číst/Zapisovat \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Návratová hodnota:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Seznam typů sestavení (např. odstavce 1,2,3, Vše najednou) textové animace. Číst/Zapisovat \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Propojený efekt tvaru se skupinou nebo ne (null) Číst/Zapisovat [IEffect](../../com.aspose.slides/ieffect).

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Propojený efekt tvaru se skupinou nebo ne (null) Číst/Zapisovat [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |