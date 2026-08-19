---
title: TextAnimation
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش انیمیشن متن.
type: docs
url: /fa/com.aspose.slides/textanimation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

نمایش انیمیشن متن.
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## متدها

| Method | Description |
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

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**مقدار بازگشتی:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write [BuildType](../../com.aspose.slides/buildtype).

**مقدار بازگشتی:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write [BuildType](../../com.aspose.slides/buildtype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Linked shape effect with group or not (null). Read/write [IEffect](../../com.aspose.slides/ieffect).

**مقدار بازگشتی:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Linked shape effect with group or not (null). Read/write [IEffect](../../com.aspose.slides/ieffect).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |