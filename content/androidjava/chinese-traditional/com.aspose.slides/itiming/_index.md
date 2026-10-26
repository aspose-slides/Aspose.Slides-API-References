---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation timing.
type: docs
url: /zh-hant/com.aspose.slides/itiming/
---```
public interface ITiming
```

表示動畫計時。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 描述持續時間加速行為效果的百分比。 |
| [setAccelerate(float value)](#setAccelerate-float-) | 描述持續時間加速行為效果的百分比。 |
| [getDecelerate()](#getDecelerate--) | 描述持續時間減速行為效果的百分比。 |
| [setDecelerate(float value)](#setDecelerate-float-) | 描述持續時間減速行為效果的百分比。 |
| [getAutoReverse()](#getAutoReverse--) | 描述是否在正向播放動畫後自動以相反方向播放動畫。 |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 描述是否在正向播放動畫後自動以相反方向播放動畫。 |
| [getDuration()](#getDuration--) | 描述動畫效果的持續時間。 |
| [setDuration(float value)](#setDuration-float-) | 描述動畫效果的持續時間。 |
| [getRepeatCount()](#getRepeatCount--) | 描述效果應重複的次數。 |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 描述效果應重複的次數。 |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 此屬性指定效果是否會持續重複直至投影片結束。 |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 此屬性指定效果是否會持續重複直至投影片結束。 |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 此屬性指定效果是否會持續重複直至下一次點擊。 |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 此屬性指定效果是否會持續重複直至下一次點擊。 |
| [getRepeatDuration()](#getRepeatDuration--) | 描述效果應重複的次數。 |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 描述效果應重複的次數。 |
| [getRestart()](#getRestart--) | 指定效果在完成後是否重新開始。 |
| [setRestart(int value)](#setRestart-int-) | 指定效果在完成後是否重新開始。 |
| [getSpeed()](#getSpeed--) | 指定加快（或減慢）計時的百分比。 |
| [setSpeed(float value)](#setSpeed-float-) | 指定加快（或減慢）計時的百分比。 |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 描述觸發後的延遲時間。 |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 描述觸發後的延遲時間。 |
| [getTriggerType()](#getTriggerType--) | 描述觸發類型。 |
| [setTriggerType(int value)](#setTriggerType-int-) | 描述觸發類型。 |
| [getRewind()](#getRewind--) | 此屬性指定在播放完成後效果是否會倒帶。 |
| [setRewind(boolean value)](#setRewind-boolean-) | 此屬性指定在播放完成後效果是否會倒帶。 |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

描述持續時間加速行為效果的百分比。讀寫 float.

**返回值:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

描述持續時間加速行為效果的百分比。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

描述持續時間減速行為效果的百分比。讀寫 float.

**返回值:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

描述持續時間減速行為效果的百分比。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

描述是否在正向播放動畫後自動以相反方向播放動畫。讀寫 boolean.

**返回值:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

描述是否在正向播放動畫後自動以相反方向播放動畫。讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

描述動畫效果的持續時間。讀寫 float.

**返回值:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

描述動畫效果的持續時間。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

描述效果應重複的次數。讀寫 float.

**返回值:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

描述效果應重複的次數。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

此屬性指定效果是否會持續重複直至投影片結束。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的計時/重複設定為「直到投影片結束」
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回值:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

此屬性指定效果是否會持續重複直至投影片結束。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的計時/重複設定為「直到投影片結束」
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

此屬性指定效果是否會持續重複直至下一次點擊。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的計時/重複設定為「直到下一次點擊」
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回值:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

此屬性指定效果是否會持續重複直至下一次點擊。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 將效果的計時/重複設定為「直到下一次點擊」
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

描述效果應重複的次數。讀寫 float.

**返回值:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

描述效果應重複的次數。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

指定效果在完成後是否重新開始。讀寫 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**返回值:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

指定效果在完成後是否重新開始。讀寫 [EffectRestartType](../../com.aspose.slides/effectrestarttype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

指定加快（或減慢）計時的百分比。讀寫 float.

**返回值:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

指定加快（或減慢）計時的百分比。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

描述觸發後的延遲時間。讀寫 float.

**返回值:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

描述觸發後的延遲時間。讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

描述觸發類型。讀寫 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**返回值:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

描述觸發類型。讀寫 [EffectTriggerType](../../com.aspose.slides/effecttriggertype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

此屬性指定在播放完成後效果是否會倒帶。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 開啟效果的計時/倒帶
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回值:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

此屬性指定在播放完成後效果是否會倒帶。讀寫 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的效果序列
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 取得主序列的第一個效果。
>      IEffect effect = effectsSequence.get_Item(0);
>      // 開啟效果的計時/倒帶
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |