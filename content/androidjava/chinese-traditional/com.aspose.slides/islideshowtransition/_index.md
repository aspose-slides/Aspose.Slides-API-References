---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: 表示投影片放映過渡。
type: docs
url: /zh-hant/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

表示投影片放映過渡。

## 方法

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | 取得或設定嵌入的音訊資料。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 取得或設定嵌入的音訊資料。 |
| [getSoundMode()](#getSoundMode--) | 設定或取得投影片過渡的音效模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 設定或取得投影片過渡的音效模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此屬性指定音訊是否會持續循環，直至投影片中出現下一個音效事件。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此屬性指定音訊是否會持續循環，直至投影片中出現下一個音效事件。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定滑鼠點擊是否會前進投影片。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定滑鼠點擊是否會前進投影片。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此屬性指定投影片是否會在特定時間後移至下一張投影片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此屬性指定投影片是否會在特定時間後移至下一張投影片。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 指定過渡應於多少毫秒之後開始。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 指定過渡應於多少毫秒之後開始。 |
| [getSpeed()](#getSpeed--) | 指定從目前投影片過渡至下一張時所使用的過渡速度。 |
| [setSpeed(int value)](#setSpeed-int-) | 指定從目前投影片過渡至下一張時所使用的過渡速度。 |
| [getValue()](#getValue--) | 投影片放映過渡值。 |
| [getType()](#getType--) | 過渡類型。 |
| [setType(int value)](#setType-int-) | 過渡類型。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 指定此音效是否為內建音效。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 指定此音效是否為內建音效。 |
| [getSoundName()](#getSoundName--) | 指定過渡音效的人類可讀名稱。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 指定過渡音效的人類可讀名稱。 |
| [getDuration()](#getDuration--) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |
| [setDuration(int value)](#setDuration-int-) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

取得或設定嵌入的音訊資料。 讀寫 [IAudio](../../com.aspose.slides/iaudio).

**傳回:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

取得或設定嵌入的音訊資料。 讀寫 [IAudio](../../com.aspose.slides/iaudio).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

設定或取得投影片過渡的音效模式。 讀寫 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**傳回:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

設定或取得投影片過渡的音效模式。 讀寫 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

此屬性指定音訊是否會持續循環，直至投影片中出現下一個音效事件。 讀寫 boolean.

**傳回:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

此屬性指定音訊是否會持續循環，直至投影片中出現下一個音效事件。 讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

指定滑鼠點擊是否會前進投影片。若未指定此屬性，則預設為 true。 讀寫 boolean.

**傳回:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

指定滑鼠點擊是否會前進投影片。若未指定此屬性，則預設為 true。 讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

此屬性指定投影片是否會在特定時間後移至下一張投影片。 讀寫  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片過渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 檢查是否已勾選「Advance Slide After」旗標
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 取得 Advance Slide After Time 的數值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

此屬性指定投影片是否會在特定時間後移至下一張投影片。 讀寫  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片過渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 檢查 Advance Slide After 旗標是否被勾選
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 取得 Advance Slide After Time 的值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

指定過渡應於多少毫秒之後開始。此設定可與 advClick 屬性一起使用。若未指定此屬性，則視為不會自動前進。 讀寫 long.

**傳回:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

指定過渡應於多少毫秒之後開始。此設定可與 advClick 屬性一起使用。若未指定此屬性，則視為不會自動前進。 讀寫 long.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

指定從目前投影片過渡至下一張時所使用的過渡速度。 讀寫 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**傳回:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

指定從目前投影片過渡至下一張時所使用的過渡速度。 讀寫 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

投影片放映過渡值。 唯讀 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**傳回:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

過渡類型。 讀寫 [TransitionType](../../com.aspose.slides/transitiontype).

**傳回:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

過渡類型。 讀寫 [TransitionType](../../com.aspose.slides/transitiontype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

指定此音效是否為內建音效。若此屬性設為 true，則產生應用程式會檢查此音效的 name 屬性是否在內建音效清單中，並可依需求提供自訂名稱或 UI。 讀寫 boolean.

**傳回:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

指定此音效是否為內建音效。若此屬性設為 true，則產生應用程式會檢查此音效的 name 屬性是否在內建音效清單中，並可依需求提供自訂名稱或 UI。 讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

指定過渡音效的人類可讀名稱。必須先指派 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 屬性才能取得或設定音效名稱。 讀寫 String.

**傳回:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

指定過渡音效的人類可讀名稱。必須先指派 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 屬性才能取得或設定音效名稱。 讀寫 String.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 讀寫 int.

--------------------

對應於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性與過渡類型自動決定持續時間。

**傳回:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 讀寫 int.

--------------------

對應於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性與過渡類型自動決定持續時間。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |