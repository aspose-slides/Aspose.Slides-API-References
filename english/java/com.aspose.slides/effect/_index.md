---
title: Effect
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents animation effect.
type: docs
weight: 161
url: /java/com.aspose.slides/effect/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Represents animation effect.
## Methods

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Returns a sequence for an effect. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Read-only [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Defines class of effect. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Defines class of effect. |
| [getType()](#getType--) | Defines type of effect. |
| [setType(int value)](#setType-int-) | Defines type of effect. |
| [getSubtype()](#getSubtype--) | Defines subtype of effect. |
| [setSubtype(int value)](#setSubtype-int-) | Defines subtype of effect. |
| [getBehaviors()](#getBehaviors--) | Returns collection of behavior for effect. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Returns collection of behavior for effect. |
| [getTiming()](#getTiming--) | Defines timing value for effect. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Defines timing value for effect. |
| [getTargetShape()](#getTargetShape--) | Returns target shape for effect. |
| [getSound()](#getSound--) | Defined embedded sound for effect. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Defined embedded sound for effect. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```


Returns a sequence for an effect. Read-only [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```


TextAnimation Read-only [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returns:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returns:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returns:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returns:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```


Returns target shape for effect. Read-only [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```


Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
