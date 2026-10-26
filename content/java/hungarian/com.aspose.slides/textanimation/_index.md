---
title: TextAnimation
second_title: Aspose.Slides Java API referencia
description: Szöveganos animációt képvisel.
type: docs
url: /hu/com.aspose.slides/textanimation/
---
**Öröklés:**  
java.lang.Object

**Az összes megvalósított interfész:**  
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)  
```
public class TextAnimation implements ITextAnimation
```

Szöveganos animációt képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Új hatást ad a jelenlegi sorozat végéhez, a csoport szöveganos animációinak végéhez. |
| [getBuildType()](#getBuildType--) | Az építési típus lista (például |
| [setBuildType(int value)](#setBuildType-int-) | Az építési típus lista (például |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | A csoporthoz vagy nem csoporthoz kapcsolt alakzat hatása (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | A csoporthoz vagy nem csoporthoz kapcsolt alakzat hatása (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Új hatást ad a jelenlegi sorozat végéhez, a csoport szöveganos animációinak végéhez. Csak akkor érvényes, ha a szövegbekezdések száma egyenlő vagy nagyobb, mint a csoport hatásainak száma!

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

A szöveganimáció építési típusának listája (például Bekezdés 1,2,3, Mind egyszerre). Olvasás/írás [BuildType](../../com.aspose.slides/buildtype).

**Visszatérési érték:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

A szöveganimáció építési típusának listája (például Bekezdés 1,2,3, Mind egyszerre). Olvasás/írás [BuildType](../../com.aspose.slides/buildtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

A csoporthoz vagy nem csoporthoz kapcsolt alakzat hatása (null). Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

A csoporthoz vagy nem csoporthoz kapcsolt alakzat hatása (null). Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |