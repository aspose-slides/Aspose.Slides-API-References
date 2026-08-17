---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /zh/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

表示幻灯片放映切换。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSound()](#getSound--) | 返回或设置嵌入的音频数据。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 返回或设置嵌入的音频数据。 |
| [getSoundMode()](#getSoundMode--) | 设置或返回幻灯片切换的声音模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 设置或返回幻灯片切换的声音模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此属性指定声音是否会循环，直到在幻灯片放映中出现下一个声音事件。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此属性指定声音是否会循环，直到在幻灯片放映中出现下一个声音事件。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定鼠标点击是否会前进到下一张幻灯片。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定鼠标点击是否会前进到下一张幻灯片。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 指定在多少毫秒后开始切换。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 指定在多少毫秒后开始切换。 |
| [getSpeed()](#getSpeed--) | 指定在从当前幻灯片过渡到下一张时使用的切换速度。 |
| [setSpeed(int value)](#setSpeed-int-) | 指定在从当前幻灯片过渡到下一张时使用的切换速度。 |
| [getValue()](#getValue--) | 幻灯片放映切换值。 |
| [getType()](#getType--) | 切换类型。 |
| [setType(int value)](#setType-int-) | 切换类型。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 指定此声音是否为内置声音。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 指定此声音是否为内置声音。 |
| [getSoundName()](#getSoundName--) | 为切换声音指定一个可读的名称。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 为切换声音指定一个可读的名称。 |
| [getDuration()](#getDuration--) | 获取或设置幻灯片切换效果的持续时间（毫秒）。 |
| [setDuration(int value)](#setDuration-int-) | 获取或设置幻灯片切换效果的持续时间（毫秒）。 |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

返回或设置嵌入的音频数据。读写 [IAudio](../../com.aspose.slides/iaudio)。

**返回:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

返回或设置嵌入的音频数据。读写 [IAudio](../../com.aspose.slides/iaudio)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

设置或返回幻灯片切换的声音模式。读写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**返回:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

设置或返回幻灯片切换的声音模式。读写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

此属性指定声音是否会循环，直到在幻灯片放映中出现下一个声音事件。读写 布尔。

**返回:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

此属性指定声音是否会循环，直到在幻灯片放映中出现下一个声音事件。读写 布尔。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

指定鼠标点击是否会前进到下一张幻灯片。如果未指定此属性，则默认假设值为 true。读写 布尔。

**返回:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

指定鼠标点击是否会前进到下一张幻灯片。如果未指定此属性，则默认假设值为 true。读写 布尔。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读/写 布尔。

**返回:**
boolean

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查是否已选中 Advance Slide After 标志
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取 Advance Slide After Time 值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读/写 布尔。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查是否已选中 Advance Slide After 标志
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取 Advance Slide After Time 值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

指定在多少毫秒后开始切换。此设置可与 advClick 属性一起使用。如果未指定此属性，则默认不进行自动前进。读写 long。

**返回:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

指定在多少毫秒后开始切换。此设置可与 advClick 属性一起使用。如果未指定此属性，则默认不进行自动前进。读写 long。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

指定在从当前幻灯片过渡到下一张时使用的切换速度。读写 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**返回:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

指定在从当前幻灯片过渡到下一张时使用的切换速度。读写 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

幻灯片放映切换值。只读 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**返回:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

切换类型。读写 [TransitionType](../../com.aspose.slides/transitiontype)。

**返回:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

切换类型。读写 [TransitionType](../../com.aspose.slides/transitiontype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序将检查为该声音指定的 name 属性是否在其内置声音列表中，并可相应地显示自定义名称或 UI。读写 布尔。

**返回:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序将检查为该声音指定的 name 属性是否在其内置声音列表中，并可相应地显示自定义名称或 UI。读写 布尔。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

为切换声音指定一个可读的名称。必须通过 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 属性来获取或设置声音名称。读写 String。

**返回:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

为切换声音指定一个可读的名称。必须通过 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 属性来获取或设置声音名称。读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

获取或设置幻灯片切换效果的持续时间（毫秒）。读/写 int。

--------------------

对应于 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，则持续时间将根据 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 属性和切换类型自动确定。

**返回:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

获取或设置幻灯片切换效果的持续时间（毫秒）。读/写 int。

--------------------

对应于 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，则持续时间将根据 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 属性和切换类型自动确定。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |