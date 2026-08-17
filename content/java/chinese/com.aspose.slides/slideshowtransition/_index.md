---
title: SlideShowTransition
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片放映过渡。
type: docs
url: /zh/com.aspose.slides/slideshowtransition/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

表示幻灯片放映过渡。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSound()](#getSound--) | 返回或设置嵌入的音频数据。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 返回或设置嵌入的音频数据。 |
| [getSoundMode()](#getSoundMode--) | 设置或返回幻灯片过渡的声音模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 设置或返回幻灯片过渡的声音模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此属性指定声音是否会循环，直至幻灯片中出现下一个声音事件。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此属性指定声音是否会循环，直至幻灯片中出现下一个声音事件。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定鼠标点击是否会推进幻灯片。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定鼠标点击是否会推进幻灯片。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此属性指定幻灯片是否在一定时间后切换到下一张幻灯片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此属性指定幻灯片是否在一定时间后切换到下一张幻灯片。 |
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
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 SlideShowTransition 实例是否相等。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数，可用于哈希算法和哈希表等数据结构。 |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

返回或设置嵌入的音频数据。读/写 [IAudio](../../com.aspose.slides/iaudio)。

**返回：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

返回或设置嵌入的音频数据。读/写 [IAudio](../../com.aspose.slides/iaudio)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

设置或返回幻灯片过渡的声音模式。读/写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**返回：**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

设置或返回幻灯片过渡的声音模式。读/写 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

此属性指定声音是否会循环，直至幻灯片中出现下一个声音事件。读/写 boolean。

**返回：**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

此属性指定声音是否会循环，直至幻灯片中出现下一个声音事件。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

指定鼠标点击是否会推进幻灯片。如果未指定此属性，则默认为 true。读/写 boolean。

**返回：**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

指定鼠标点击是否会推进幻灯片。如果未指定此属性，则默认为 true。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

此属性指定幻灯片是否在一定时间后切换到下一张幻灯片。读/写 boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一个幻灯片过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查“Advance Slide After”标志是否已勾选
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取Advance Slide After Time值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

此属性指定幻灯片是否在一定时间后切换到下一张幻灯片。读/写 boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 获取第一个幻灯片过渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 检查“Advance Slide After”标志是否已勾选
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 获取Advance Slide After Time值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

指定过渡应在多少毫秒后开始。此设置可与 advClick 属性一起使用。如果未指定此属性，则默认不自动前进。读/写 long。

**返回：**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

指定过渡应在多少毫秒后开始。此设置可与 advClick 属性一起使用。如果未指定此属性，则默认不自动前进。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。读/写 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**返回：**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。读/写 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

幻灯片放映过渡值。只读 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**返回：**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

过渡类型。读/写 [TransitionType](../../com.aspose.slides/transitiontype)。

**返回：**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

过渡类型。读/写 [TransitionType](../../com.aspose.slides/transitiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序会检查该声音在内置声音列表中的 name 属性，并相应提供自定义名称或 UI。读/写 boolean。

**返回：**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

指定此声音是否为内置声音。如果此属性设为 true，则生成应用程序会检查该声音在内置声音列表中的 name 属性，并相应提供自定义名称或 UI。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

指定过渡声音的人类可读名称。必须先赋值 Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) 属性才能获取或设置声音名称。读/写 String。

**返回：**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

指定过渡声音的人类可读名称。必须先赋值 Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) 属性才能获取或设置声音名称。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

获取或设置幻灯片过渡效果的持续时间（毫秒）。读/写 int。

--------------------

对应 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，持续时间将根据 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 属性和过渡类型自动确定。

**返回：**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

获取或设置幻灯片过渡效果的持续时间（毫秒）。读/写 int。

--------------------

对应 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，持续时间将根据 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 属性和过渡类型自动确定。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 SlideShowTransition 实例是否相等。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与当前 SlideShowTransition 比较的实例。 |

**返回：**
boolean -  **true**  如果指定的 SlideShowTransition 与当前 SlideShowTransition 相等；否则 **false** 。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数，可用于哈希算法和哈希表等数据结构。

**返回：**
int - 23454

--------------------

为使编译器满意而覆盖。始终返回常量，因为对象是可变的。