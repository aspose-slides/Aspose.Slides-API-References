---
title: Timing
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画计时。
type: docs
url: /zh/com.aspose.slides/timing/
---
**继承：**
java.lang.Object

**全部实现的接口：**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

表示动画计时。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 描述加速行为效果的持续时间百分比。 |
| [setAccelerate(float value)](#setAccelerate-float-) | 描述加速行为效果的持续时间百分比。 |
| [getDecelerate()](#getDecelerate--) | 描述减速行为效果的持续时间百分比。 |
| [setDecelerate(float value)](#setDecelerate-float-) | 描述减速行为效果的持续时间百分比。 |
| [getAutoReverse()](#getAutoReverse--) | 描述在正向播放后是否自动反向播放动画。 |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 描述在正向播放后是否自动反向播放动画。 |
| [getDuration()](#getDuration--) | 描述动画效果的持续时间。 |
| [setDuration(float value)](#setDuration-float-) | 描述动画效果的持续时间。 |
| [getRepeatCount()](#getRepeatCount--) | 描述效果应重复的次数。 |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 描述效果应重复的次数。 |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 此属性指定效果是否会重复至幻灯片结束。 |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 此属性指定效果是否会重复至幻灯片结束。 |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 此属性指定效果是否会重复至下一次点击。 |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 此属性指定效果是否会重复至下一次点击。 |
| [getRepeatDuration()](#getRepeatDuration--) | 描述效果应重复的次数。 |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 描述效果应重复的次数。 |
| [getRestart()](#getRestart--) | 指定效果在完成后是否重新启动。 |
| [setRestart(int value)](#setRestart-int-) | 指定效果在完成后是否重新启动。 |
| [getRewind()](#getRewind--) | 此属性指定在播放完成后效果是否会倒回。 |
| [setRewind(boolean value)](#setRewind-boolean-) | 此属性指定在播放完成后效果是否会倒回。 |
| [getSpeed()](#getSpeed--) | 指定计时加速（或减速）的百分比。 |
| [setSpeed(float value)](#setSpeed-float-) | 指定计时加速（或减速）的百分比。 |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 描述触发后的延迟时间。 |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 描述触发后的延迟时间。 |
| [getTriggerType()](#getTriggerType--) | 描述触发类型。 |
| [setTriggerType(int value)](#setTriggerType-int-) | 描述触发类型。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```


描述加速行为效果的持续时间百分比。可读写 float。

**返回：**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```


描述加速行为效果的持续时间百分比。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```


描述减速行为效果的持续时间百分比。可读写 float。

**返回：**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```


描述减速行为效果的持续时间百分比。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```


描述在正向播放后是否自动反向播放动画。可读写 boolean。

**返回：**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```


描述在正向播放后是否自动反向播放动画。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public final float getDuration()
```


描述动画效果的持续时间。可读写 float。

**返回：**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```


描述动画效果的持续时间。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```


描述效果应重复的次数。可读写 float。

**返回：**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```


描述效果应重复的次数。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```


此属性指定效果是否会重复至幻灯片结束。可读写 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的计时/重复设置为“直到幻灯片结束”
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

This attribute specifies if the effect will repeat until the end of the slide. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的计时/重复设置为“直到幻灯片结束”
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
```
public final boolean getRepeatUntilNextClick()
```

This attribute specifies if the effect will repeat until the next click. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的计时/重复更改为 “直到下一次点击”
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

This attribute specifies if the effect will repeat until the next click. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的计时/重复更改为 “直到下一次点击”
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
public final float getRepeatDuration()
```

Describes the number of times the effect should repeat. Read/write float.

**Returns:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```
Describes the number of times the effect should repeat. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

Specifies if a effect is to restart after complete. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Returns:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```
Specifies if a effect is to restart after complete. Read/write [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```
This attribute specifies if the effect will rewind when done playing. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 打开效果的计时/倒回。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

This attribute specifies if the effect will rewind when done playing. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 打开效果的计时/倒回。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

指定计时加速（或减速）的百分比。可读写 float。

**Returns:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

Specifies the percentage by which to speed up (or slow down) the timing. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

Describes delay time after trigger. Read/write float.

**Returns:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

Describes delay time after trigger. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```
 


Describes trigger type. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Returns:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

Describes trigger type. Read/write [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject