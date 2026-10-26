---
title: ITiming
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画计时。
type: docs
url: /zh/com.aspose.slides/itiming/
---```
public interface ITiming
```

表示动画计时。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 描述加速行为效果的持续时间百分比。 |
| [setAccelerate(float value)](#setAccelerate-float-) | 描述加速行为效果的持续时间百分比。 |
| [getDecelerate()](#getDecelerate--) | 描述减速行为效果的持续时间百分比。 |
| [setDecelerate(float value)](#setDecelerate-float-) | 描述减速行为效果的持续时间百分比。 |
| [getAutoReverse()](#getAutoReverse--) | 描述在正向播放后是否自动以相反方向播放动画。 |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 描述在正向播放后是否自动以相反方向播放动画。 |
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
| [getRestart()](#getRestart--) | 指定效果在完成后是否重新开始。 |
| [setRestart(int value)](#setRestart-int-) | 指定效果在完成后是否重新开始。 |
| [getSpeed()](#getSpeed--) | 指定将时间加快（或放慢）的百分比。 |
| [setSpeed(float value)](#setSpeed-float-) | 指定将时间加快（或放慢）的百分比。 |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 描述触发后的延迟时间。 |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 描述触发后的延迟时间。 |
| [getTriggerType()](#getTriggerType--) | 描述触发类型。 |
| [setTriggerType(int value)](#setTriggerType-int-) | 描述触发类型。 |
| [getRewind()](#getRewind--) | 此属性指定在播放完成后是否倒回效果。 |
| [setRewind(boolean value)](#setRewind-boolean-) | 此属性指定在播放完成后是否倒回效果。 |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

描述加速行为效果的持续时间百分比。 读/写 float.

**返回：**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

描述加速行为效果的持续时间百分比。 读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

描述减速行为效果的持续时间百分比。 读/写 float.

**返回：**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

描述减速行为效果的持续时间百分比。 读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

描述在正向播放后是否自动以相反方向播放动画。 读/写 boolean.

**返回：**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

描述在正向播放后是否自动以相反方向播放动画。 读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

描述动画效果的持续时间。 读/写 float.

**返回：**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

描述动画效果的持续时间。 读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

描述效果应重复的次数。 读/写 float.

**返回：**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

描述效果应重复的次数。 读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

此属性指定效果是否会重复直到幻灯片结束。 读/写 boolean.

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

This attribute specifies if the effect will repeat until the end of the slide. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的 Timing/Repeat 更改为 “直到幻灯片结束”
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
```
public abstract boolean getRepeatUntilNextClick()
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
>      // 将效果的 Timing/Repeat 更改为 “直到下一次点击”
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

This attribute specifies if the effect will repeat until the next click. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 获取主序列的第一个效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 将效果的 Timing/Repeat 更改为 “直到下一次点击”
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

指定效果是否在完成后重新启动。 读/写 [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

指定加快（或减慢）计时的百分比。读/写 float.

**返回：**
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

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```
This attribute specifies if the effect will rewind when done playing. Read/write boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>       // 获取第一张幻灯片的效果序列
>       ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>       // 获取主序列的第一个效果。
>       IEffect effect = effectsSequence.get_Item(0);
>       // 打开效果的 Timing/Rewind。
>       effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)


此属性指定在播放完成后是否倒回效果。 读/写 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Turn the effect Timing/Rewind on.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |