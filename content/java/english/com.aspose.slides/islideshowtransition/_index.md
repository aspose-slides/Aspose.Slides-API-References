---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Represents slide show transition.
## Methods

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | Returns or sets the embedded audio data. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Returns or sets the embedded audio data. |
| [getSoundMode()](#getSoundMode--) | Set or returns sound mode for slide transition. |
| [setSoundMode(int value)](#setSoundMode-int-) | Set or returns sound mode for slide transition. |
| [getSoundLoop()](#getSoundLoop--) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifies whether a mouse click will advance the slide or not. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifies whether a mouse click will advance the slide or not. |
| [getAdvanceAfter()](#getAdvanceAfter--) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Specifies the time, in milliseconds, after which the transition should start. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Specifies the time, in milliseconds, after which the transition should start. |
| [getSpeed()](#getSpeed--) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [setSpeed(int value)](#setSpeed-int-) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [getValue()](#getValue--) | Slide show transition value. |
| [getType()](#getType--) | Type of transition. |
| [setType(int value)](#setType-int-) | Type of transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Specifies whether or not this sound is a built-in sound. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Specifies whether or not this sound is a built-in sound. |
| [getSoundName()](#getSoundName--) | Specifies a human readable name for the sound of the transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifies a human readable name for the sound of the transition. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Returns or sets the embedded audio data. Read-write [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Returns or sets the embedded audio data. Read-write [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```


Set or returns sound mode for slide transition. Read-write [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Returns:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```


Set or returns sound mode for slide transition. Read-write [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read-write boolean.

**Returns:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read-write boolean.

**Returns:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```


This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```


Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read-write long.

**Returns:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```


Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read-write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```


Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returns:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```


Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```


Slide show transition value. Read-only [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returns:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```


Type of transition. Read-write [TransitionType](../../com.aspose.slides/transitiontype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Type of transition. Read-write [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```


Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Returns:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```


Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```


Specifies a human readable name for the sound of the transition. The (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String.

**Returns:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```


Specifies a human readable name for the sound of the transition. The (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

