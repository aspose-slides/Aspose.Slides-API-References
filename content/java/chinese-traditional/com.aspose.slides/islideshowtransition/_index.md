---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /zh-hant/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

表示投影片放映過渡。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSound()](#getSound--) | 返回或設定嵌入的音訊資料。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 返回或設定嵌入的音訊資料。 |
| [getSoundMode()](#getSoundMode--) | 設定或返回投影片過渡的音效模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 設定或返回投影片過渡的音效模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此屬性指定音訊是否會持續循環，直到投影片放映中下一個音訊事件發生。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此屬性指定音訊是否會持續循環，直到投影片放映中下一個音訊事件發生。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定滑鼠點擊是否會前進投影片。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定滑鼠點擊是否會前進投影片。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此屬性指定投影片放映是否會在特定時間後移至下一張投影片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此屬性指定投影片放映是否會在特定時間後移至下一張投影片。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 指定過渡應在多少毫秒之後開始。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 指定過渡應在多少毫秒之後開始。 |
| [getSpeed()](#getSpeed--) | 指定從目前投影片過渡至下一張投影片時使用的過渡速度。 |
| [setSpeed(int value)](#setSpeed-int-) | 指定從目前投影片過渡至下一張投影片時使用的過渡速度。 |
| [getValue()](#getValue--) | 投影片放映過渡值。 |
| [getType()](#getType--) | 過渡類型。 |
| [setType(int value)](#setType-int-) | 過渡類型。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 指定此音訊是否為內建音效。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 指定此音訊是否為內建音效。 |
| [getSoundName()](#getSoundName--) | 為過渡的音效指定一個易讀的名稱。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 為過渡的音效指定一個易讀的名稱。 |
| [getDuration()](#getDuration--) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |
| [setDuration(int value)](#setDuration-int-) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

返回或設定嵌入的音訊資料。Read-write [IAudio](../../com.aspose.slides/iaudio)。

**返回值:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

返回或設定嵌入的音訊資料。Read-write [IAudio](../../com.aspose.slides/iaudio)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

設定或返回投影片過渡的音效模式。Read-write [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**返回值:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

設定或返回投影片過渡的音效模式。Read-write [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

此屬性指定音訊是否會持續循環，直到投影片放映中下一個音訊事件發生。Read-write boolean。

**返回值:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

此屬性指定音訊是否會持續循環，直到投影片放映中下一個音訊事件發生。Read-write boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設為 true。Read-write boolean。

**返回值:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設為 true。Read-write boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

此屬性指定投影片放映是否會在特定時間後移至下一張投影片。Read/write  boolean 。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的過渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 檢查 Advance Slide After 旗標是否已勾選
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 取得 Advance Slide After Time 值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

此屬性指定投影片放映是否會在特定時間後移至下一張投影片。Read/write  boolean 。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的過渡
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // 檢查 Advance Slide After 旗標是否已勾選
>      if (slideTransition.getAdvanceAfter())
>      {
>          // 取得 Advance Slide After Time 值
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

指定過渡應在多少毫秒之後開始。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則視為不會自動前進。Read-write long。

**返回值:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

指定過渡應在多少毫秒之後開始。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則視為不會自動前進。Read-write long。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

指定從目前投影片過渡至下一張投影片時使用的過渡速度。Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**返回值:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

指定從目前投影片過渡至下一張投影片時使用的過渡速度。Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

投影片放映過渡值。Read-only [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**返回值:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

過渡類型。Read-write [TransitionType](../../com.aspose.slides/transitiontype)。

**返回值:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

過渡類型。Read-write [TransitionType](../../com.aspose.slides/transitiontype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

指定此音訊是否為內建音效。如果此屬性設為 true，則生成應用程式會檢查此音訊在內建音效清單中指定的名稱屬性，並可依需要顯示自訂名稱或 UI。Read-write boolean。

**返回值:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

指定此音訊是否為內建音效。如果此屬性設為 true，則生成應用程式會檢查此音訊在內建音效清單中指定的名稱屬性，並可依需要顯示自訂名稱或 UI。Read-write boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

為過渡的音效指定一個易讀的名稱。必須使用 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 屬性來取得或設定音效名稱。Read-write String。

**返回值:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

為過渡的音效指定一個易讀的名稱。必須使用 \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 屬性來取得或設定音效名稱。Read-write String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

取得或設定投影片過渡效果的持續時間（以毫秒為單位）。Read/write int。

--------------------

對應於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則持續時間會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性和過渡類型自動決定。

**返回值:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

取得或設定投影片過渡效果的持續時間（以毫秒為單位）。Read/write int。

--------------------

對應於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則持續時間會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性和過渡類型自動決定。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |