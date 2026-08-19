---
title: TextAnimation
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje textovou animaci.
type: docs
url: /cs/com.aspose.slides/textanimation/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Reprezentuje textovou animaci.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. |
| [getBuildType()](#getBuildType--) | Seznam typu sestavení (např. |
| [setBuildType(int value)](#setBuildType-int-) | Seznam typu sestavení (např. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Propojený efekt tvaru se skupinou nebo ne (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Propojený efekt tvaru se skupinou nebo ne (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Přidá nový efekt na konec aktuální sekvence do konce skupinových textových animací. Platí pouze, pokud je počet odstavců textu roven nebo větší než počet efektů v této skupině!

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
public final int getBuildType()
```

Seznam typu sestavení (např. odstavec 1,2,3, Vše najednou) textové animace. Čtení/Zápis [BuildType](../../com.aspose.slides/buildtype).

**Návratová hodnota:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Seznam typu sestavení (např. odstavec 1,2,3, Vše najednou) textové animace. Čtení/Zápis [BuildType](../../com.aspose.slides/buildtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Propojený efekt tvaru se skupinou nebo ne (null). Čtení/Zápis [IEffect](../../com.aspose.slides/ieffect).

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Propojený efekt tvaru se skupinou nebo ne (null). Čtení/Zápis [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |