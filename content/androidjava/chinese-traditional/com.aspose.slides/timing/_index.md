---
title: Timing
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示動畫計時。
type: docs
url: /zh-hant/com.aspose.slides/timing/
---
**繼承：**
java.lang.Object

**全部已實作的介面：**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

表示動畫計時。
## 方法

| Method | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 描述持續時間加速行為效果的百分比。 |
| [setAccelerate(float value)](#setAccelerate-float-) | 描述持續時間加速行為效果的百分比。 |
| [getDecelerate()](#getDecelerate--) | 描述持續時間減速行為效果的百分比。 |
| [setDecelerate(float value)](#setDecelerate-float-) | 描述持續時間減速行為效果的百分比。 |
| [getAutoReverse()](#getAutoReverse--) | 描述在正向播放後是否自動以相反方向播放動畫。 |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 描述在正向播放後是否自動以相反方向播放動畫。 |
| [getDuration()](#getDuration--) | 描述動畫效果的持續時間。 |
| [setDuration(float value)](#setDuration-float-) | 描述動畫效果的持續時間。 |
| [getRepeatCount()](#getRepeatCount--) | 描述效果應重複的次數。 |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 描述效果應重複的次數。 |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 此屬性指定效果是否會持續到投影片結束。 |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 此屬性指定效果是否會持續到投影片結束。 |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 此層屬性指定效果是否會持續到下一次點擊。 |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 此層屬性指定效果是否會持續到下一次點擊。 |
| [getRepeatDuration()](#getRepeatDuration--) | 描述效果應重複的次數。 |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 描述效果應重複的次數。 |
| [getRestart()](#getRestart--) | 指定效果完成後是否重新啟動。 |
| [setRestart(int value)](#setRestart-int-) | 指定效果完成後是否重新啟動。 |
| [getRewind()](#getRewind--) | 此屬性指定效果播放完畢後是否倒帶。 |
| [setRewind(boolean value)](#setRewind-boolean-) | 此屬性指定效果播放完畢後是否倒帶。 |
| [getSpeed()](#getSpeed--) | 指定加速（或減速）計時的百分比。 |
| [setSpeed(float value)](#setSpeed-float-) | 指定加速（或減速）計時的百分比。 |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 描述觸發後的延遲時間。 |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 描述觸發後的延遲時間。 |
| [getTriggerType()](#getTriggerType--) | 描述觸發類型。 |
| [setTriggerType(int value)](#setTriggerType-int-) | 描述觸發類型。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

描述持續時間加速行為效果的百分比。 可讀寫 float。

**傳回：**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

描述持續時間加速行為效果的百分比。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

描述持續時間減速行為效果的百分比。 可讀寫 float。

**傳回：**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

描述持續時間減速行為效果的百分比。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

描述在正向播放後是否自動以相反方向播放動畫。 可讀寫 boolean。

**傳回：**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

描述在正向播放後是否自動以相反方向播放動畫。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

描述動畫效果的持續時間。 可讀寫 float。

**傳回：**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

描述動畫效果的持續時間。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

描述效果應重複的次數。 可讀寫 float。

**傳回：**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

描述效果應重複的次數。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

此屬性指定效果是否會持續到投影片結束。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的 Timing/Repeat 改為「直到投影片結束」
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

此屬性指定效果是否會持續到投影片結束。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的 Timing/Repeat 改為「直到投影片結束」
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

此屬性指定效果是否會持續到下一次點擊。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的 Timing/Repeat 改為「直到下一次點擊」
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

此屬性指定效果是否會持續到下一次點擊。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的 Timing/Repeat 改為「直到下一次點擊」
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

描述效果應重複的次數。 可讀寫 float。

**傳回：**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

描述效果應重複的次數。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

指定效果完成後是否重新啟動。 可讀寫 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**傳回：**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

指定效果完成後是否重新啟動。 可讀寫 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

此屬性指定效果播放完畢後是否倒帶。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 開啟效果的 Timing/Rewind。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

此屬性指定效果播放完畢後是否倒帶。 可讀寫 boolean。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 開啟效果的 Timing/Rewind。
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

指定加速（或減速）計時的百分比。 可讀寫 float。

**傳回：**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

指定加速（或減速）計時的百分比。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

描述觸發後的延遲時間。 可讀寫 float。

**傳回：**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

描述觸發後的延遲時間。 可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

描述觸發類型。 可讀寫 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**傳回：**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

描述觸發類型。 可讀寫 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。 唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject