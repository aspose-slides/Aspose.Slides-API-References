---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片放映过渡。
type: docs
url: /zh/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

表示幻灯片放映过渡。
## 方法

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | 返回或设置嵌入的音频数据。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 返回或设置嵌入的音频数据。 |
| [getSoundMode()](#getSoundMode--) | 设置或返回幻灯片过渡的声音模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 设置或返回幻灯片过渡的声音模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此属性指定声音是否会循环，直至幻灯片放映中出现下一个声音事件。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此属性指定声音是否会循环，直至幻灯片放映中出现下一个声音事件。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定鼠标点击是否会推进幻灯片。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定鼠标点击是否会推进幻灯片。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此属性指定幻灯片在一定时间后是否会移动到下一张幻灯片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此属性指定幻灯片在一定时间后是否会移动到下一张幻灯片。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 指定过渡应在多少毫秒后开始。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 指定过渡应在多少毫秒后开始。 |
| [getSpeed()](#getSpeed--) | 指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。 |
| [setSpeed(int value)](#setSpeed-int-) | 指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。 |
| [getValue()](#getValue--) | 幻灯片放映过渡值。 |
| [getType()](#getType--) | 过渡类型。 |
| [setType(int value)](#setType-int-) | 过渡类型。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 指定此声音是否为内置声音。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 指定此声音是否为内置声音。 |
| [getSoundName()](#getSoundName--) | 指定过渡声音的人类可读名称。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 指定过渡声音的人类可读名称。 |
| [getDuration()](#getDuration--) | 获取或设置幻灯片过渡效果的持续时间（毫秒）。 |
| [setDuration(int value)](#setDuration-int-) | 获取或设置幻灯片过渡效果的持续时间（毫秒）。 |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

返回或设置嵌入的音频数据。读写 [IAudio](../../com.aspose.slides/iaudio)。

**返回：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

返回或设置嵌入的音频数据。读写 [IAudio](../../com.aspose.slides/iaudio)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

设置或返回幻灯片过渡的声音模式。读写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**返回：**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

设置或返回幻灯片过渡的声音模式。读写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

此属性指定声音是否会循环，直至幻灯片放映中出现下一个声音事件。读写 boolean。

**返回：**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

此属性指定声音是否会循环，直至幻灯片放映中出现下一个声音事件。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

指定鼠标点击是否会推进幻灯片。如果未指定此属性，则默认值为 true。读写 boolean。

**返回：**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

指定鼠标点击是否会推进幻灯片。如果未指定此属性，则默认值为 true。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

此属性指定幻灯片在一定时间后是否会移动到下一张幻灯片。读/写 boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一个幻灯片过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查是否选中 Advance Slide After 标志
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取 Advance Slide After 时间值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public abstract void setAdvanceAfter(boolean value)
```
This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一个幻灯片过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查是否选中 Advance Slide After 标志
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取 Advance Slide After 时间值
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
 
指定过渡声音的人类可读名称。必须分配 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 属性以获取或设置声音名称。读写 String.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```
 
Gets or sets the duration of the slide transition effect in milliseconds. Read/write int.

--------------------

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**Returns:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)


获取或设置幻灯片过渡效果的持续时间（毫秒）。读/写 int。

--------------------

对应 PresentationML 模式中 p:transition 元素的 p14:dur 属性。如果未设置，则持续时间将基于 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 属性和过渡类型自动确定。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |