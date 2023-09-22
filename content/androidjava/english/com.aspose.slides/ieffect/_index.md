---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /com.aspose.slides/ieffect/
---```
public interface IEffect
```

Represents animation effect.
## Methods

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Returns a sequence for an effect. |
| [getTextAnimation()](#getTextAnimation--) | Returns text animation. |
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
| [getStopPreviousSound()](#getStopPreviousSound--) | This attribute specifies if the animation effect stops the previous sound. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | This attribute specifies if the animation effect stops the previous sound. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Defined an after animation type for effect. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Defined an after animation type for effect. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Defined an after animation color for effect. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Defined an after animation color for effect. |
| [getAnimateTextType()](#getAnimateTextType--) | Defines an animate text type for effect. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Defines an animate text type for effect. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Defines a delay between animated text parts (words or letters). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Defines a delay between animated text parts (words or letters). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Returns a sequence for an effect. Read-only [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Returns text animation. Read-only [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returns:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returns:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returns:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returns:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Returns target shape for effect. Read-only [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
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
public abstract void setSound(IAudio value)
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

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Get the first effect of the second slide.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Change the second effect Enhancements/Sound to "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Get the first effect of the second slide.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Change the second effect Enhancements/Sound to "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Defined an after animation type for effect. Read/write  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation to "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Defined an after animation type for effect. Read/write  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation to "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Defined an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation type to "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Set the effect After animation color.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Defined an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation type to "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Set the effect After animation color.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Set the delay between animated text parts to 20% of effect duration.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Set the delay between animated text parts to 20% of effect duration.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

