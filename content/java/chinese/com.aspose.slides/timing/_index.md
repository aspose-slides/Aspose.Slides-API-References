---
title: Timing
second_title: Aspose.Slides for Java API 参考
description: 表示动画计时。
type: docs
url: /zh/com.aspose.slides/timing/
---
**继承:**  
java.lang.Object  

**所有实现的接口:**  
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject  
```
public class Timing implements ITiming, IDOMObject
```

表示动画计时。  
## 方法

| Method | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 描述持续时间加速行为效果的百分比。 |
| [setAccelerate(float value)](#setAccelerate-float-) | 描述持续时间加速行为效果的百分比。 |
| [getDecelerate()](#getDecelerate--) | 描述持续时间减速行为效果的百分比。 |
| [setDecelerate(float value)](#setDecelerate-float-) | 描述持续时间减速行为效果的百分比。 |
| [getAutoReverse()](#getAutoReverse--) | 描述在正向播放后是否自动反向播放动画。 |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 描述在正向播放后是否自动反向播放动画。 |
| [getDuration()](#getDuration--) | 描述动画效果的持续时间。 |
| [setDuration(float value)](#setDuration-float-) | 描述动画效果的持续时间。 |
| [getRepeatCount()](#getRepeatCount--) | 描述效果应重复的次数。 |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 描述效果应重复的次数。 |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 此属性指定效果是否会重复直到幻灯片结束。 |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 此属性指定效果是否会重复直到幻灯片结束。 |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 此属性指定效果是否会重复直到下一次点击。 |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 此属性指定效果是否会重复直到下一次点击。 |
| [getRepeatDuration()](#getRepeatDuration--) | 描述效果应重复的次数。 |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 描述效果应重复的次数。 |
| [getRestart()](#getRestart--) | 指定效果是否在完成后重新启动。 |
| [setRestart(int value)](#setRestart-int-) | 指定效果是否在完成后重新启动。 |
| [getRewind()](#getRewind--) | 此属性指定在播放完成后是否倒回效果。 |
| [setRewind(boolean value)](#setRewind-boolean-) | 此属性指定在播放完成后是否倒回效果。 |
| [getSpeed()](#getSpeed--) | 指定加速（或减速）计时的百分比。 |
| [setSpeed(float value)](#setSpeed-float-) | 指定加速（或减速）计时的百分比。 |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 描述触发后的延迟时间。 |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 描述触发后的延迟时间。 |
| [getTriggerType()](#getTriggerType--) | 描述触发类型。 |
| [setTriggerType(int value)](#setTriggerType-int-) | 描述触发类型。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

描述持续时间加速行为效果的百分比。 读/写 float。

**返回：**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

描述持续时间加速行为效果的百分比。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

描述持续时间减速行为效果的百分比。 读/写 float。

**返回：**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

描述持续时间减速行为效果的百分比。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

描述在正向播放后是否自动反向播放动画。 读/写 boolean。

**返回：**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

描述在正向播放后是否自动反向播放动画。 读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

描述动画效果的持续时间。 读/写 float。

**返回：**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

描述动画效果的持续时间。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

描述效果应重复的次数。 读/写 float。

**返回：**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

描述效果应重复的次数。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

此属性指定效果是否会重复直到幻灯片结束。 读/写 boolean。

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

**返回：**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

此属性指定效果是否会重复直到幻灯片结束。 读/写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的 Timing/Repeat 更改为 "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

此属性指定效果是否会重复直到下一次点击。 读/写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的 Timing/Repeat 更改为 "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

此属性指定效果是否会重复直到下一次点击。 读/写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的 Timing/Repeat 更改为 "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

描述效果应重复的次数。 读/写 float。

**返回：**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

描述效果应重复的次数。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

指定效果是否在完成后重新启动。 读/写 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**返回：**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

指定效果是否在完成后重新启动。 读/写 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

此属性指定在播放完成后是否倒回效果。 读/写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 打开效果的 Timing/Rewind。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回：**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

此属性指定在播放完成后是否倒回效果。 读/写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 打开效果的 Timing/Rewind。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

指定加速（或减速）计时的百分比。 读/写 float。

**返回：**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

指定加速（或减速）计时的百分比。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

描述触发后的延迟时间。 读/写 float。

**返回：**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

描述触发后的延迟时间。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

描述触发类型。 读/写 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**返回：**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

描述触发类型。 读/写 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。 只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject