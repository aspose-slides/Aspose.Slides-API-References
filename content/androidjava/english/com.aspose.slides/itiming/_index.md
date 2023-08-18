---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation timing.
type: docs
weight: 1084
url: /com.aspose.slides/itiming/
---```
public interface ITiming
```

Represents animation timing.
## Methods

| Method | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Describes the percentage of duration accelerate behavior effect. |
| [setAccelerate(float value)](#setAccelerate-float-) | Describes the percentage of duration accelerate behavior effect. |
| [getDecelerate()](#getDecelerate--) | Describes the percentage of duration decelerate behavior effect. |
| [setDecelerate(float value)](#setDecelerate-float-) | Describes the percentage of duration decelerate behavior effect. |
| [getAutoReverse()](#getAutoReverse--) | Describes whether to automatically play the animation in reverse after playing it in the forward direction. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Describes whether to automatically play the animation in reverse after playing it in the forward direction. |
| [getDuration()](#getDuration--) | Describes the duration of animation effect. |
| [setDuration(float value)](#setDuration-float-) | Describes the duration of animation effect. |
| [getRepeatCount()](#getRepeatCount--) | Describes the number of times the effect should repeat. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Describes the number of times the effect should repeat. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | This attribute specifies if the effect will repeat until the end of the slide. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | This attribute specifies if the effect will repeat until the end of the slide. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | This attribute specifies if the effect will repeat until the next click. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | This attribute specifies if the effect will repeat until the next click. |
| [getRepeatDuration()](#getRepeatDuration--) | Describes the number of times the effect should repeat. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Describes the number of times the effect should repeat. |
| [getRestart()](#getRestart--) | Specifies if a effect is to restart after complete. |
| [setRestart(int value)](#setRestart-int-) | Specifies if a effect is to restart after complete. |
| [getSpeed()](#getSpeed--) | Specifies the percentage by which to speed up (or slow down) the timing. |
| [setSpeed(float value)](#setSpeed-float-) | Specifies the percentage by which to speed up (or slow down) the timing. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Describes delay time after trigger. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Describes delay time after trigger. |
| [getTriggerType()](#getTriggerType--) | Describes trigger type. |
| [setTriggerType(int value)](#setTriggerType-int-) | Describes trigger type. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```


Describes the percentage of duration accelerate behavior effect. Read/write float.

**Returns:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```


Describes the percentage of duration accelerate behavior effect. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```


Describes the percentage of duration decelerate behavior effect. Read/write float.

**Returns:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```


Describes the percentage of duration decelerate behavior effect. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```


Describes whether to automatically play the animation in reverse after playing it in the forward direction. Read/write boolean.

**Returns:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```


Describes whether to automatically play the animation in reverse after playing it in the forward direction. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```


Describes the duration of animation effect. Read/write float.

**Returns:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```


Describes the duration of animation effect. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```


Describes the number of times the effect should repeat. Read/write float.

**Returns:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```


Describes the number of times the effect should repeat. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```


This attribute specifies if the effect will repeat until the end of the slide. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```


This attribute specifies if the effect will repeat until the end of the slide. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```


This attribute specifies if the effect will repeat until the next click. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```


This attribute specifies if the effect will repeat until the next click. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```


Describes the number of times the effect should repeat. Read/write float.

**Returns:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```


Describes the number of times the effect should repeat. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```


Specifies if a effect is to restart after complete. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Returns:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```


Specifies if a effect is to restart after complete. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```


Specifies the percentage by which to speed up (or slow down) the timing. Read/write float.

**Returns:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```


Specifies the percentage by which to speed up (or slow down) the timing. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```


Describes delay time after trigger. Read/write float.

**Returns:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```


Describes delay time after trigger. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```


Describes trigger type. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Returns:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```


Describes trigger type. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

