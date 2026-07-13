---
title: TextAnimation
second_title: Aspose.Slides dla Androida za pośrednictwem Java API
description: Reprezentuje animację tekstu.
type: docs
url: /pl/com.aspose.slides/textanimation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Represent text animation.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Add new effect to the end of current sequence to end of group text animations. |
| [getBuildType()](#getBuildType--) | List of build type (for exp. |
| [setBuildType(int value)](#setBuildType-int-) | List of build type (for exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Linked shape effect with group or not (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Linked shape effect with group or not (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Add new effect to the end of current sequence to end of group text animations. Only valid if count of text paragraphs equal or greater of counts effect of this group!

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write [BuildType](../../com.aspose.slides/buildtype).

**Zwraca:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write [BuildType](../../com.aspose.slides/buildtype).

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Linked shape effect with group or not (null). Read/write [IEffect](../../com.aspose.slides/ieffect).

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Linked shape effect with group or not (null). Read/write [IEffect](../../com.aspose.slides/ieffect).

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |