---
title: TextAnimation
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje animaci textu.
type: docs
url: /cs/com.aspose.slides/textanimation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Reprezentuje animaci textu.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Přidá nový efekt na konec aktuální sekvence do konce skupinových animací textu. |
| [getBuildType()](#getBuildType--) | Seznam typů sestavení (např. |
| [setBuildType(int value)](#setBuildType-int-) | Seznam typů sestavení (např. |
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


Přidá nový efekt na konec aktuální sekvence do konce skupinových animací textu. Platí pouze tehdy, pokud počet odstavců textu je roven nebo větší než počet efektů v této skupině!

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


Seznam typů sestavení (např. odstavce 1,2,3, Vše najednou) animace textu. Čtení/zápis [BuildType](../../com.aspose.slides/buildtype).

**Návratová hodnota:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Seznam typů sestavení (např. odstavce 1,2,3, Vše najednou) animace textu. Čtení/zápis [BuildType](../../com.aspose.slides/buildtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Propojený efekt tvaru se skupinou nebo ne (null). Čtení/zápis [IEffect](../../com.aspose.slides/ieffect).

**Návratová hodnota:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Propojený efekt tvaru se skupinou nebo ne (null). Čtení/zápis [IEffect](../../com.aspose.slides/ieffect).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |