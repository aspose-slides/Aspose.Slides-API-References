---
title: SlideShowTransition
second_title: 透過 Java API 參考的 Aspose.Slides for Android
description: 表示投影片放映過渡。
type: docs
url: /zh-hant/com.aspose.slides/slideshowtransition/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面：**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

表示投影片放映過渡。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSound()](#getSound--) | 返回或設定嵌入的音訊資料。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 返回或設定嵌入的音訊資料。 |
| [getSoundMode()](#getSoundMode--) | 設定或返回投影片過渡的聲音模式。 |
| [setSoundMode(int value)](#setSoundMode-int-) | 設定或返回投影片過渡的聲音模式。 |
| [getSoundLoop()](#getSoundLoop--) | 此屬性指定聲音是否會持續循環，直到投影片放映中出現下一個聲音事件。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 此屬性指定聲音是否會持續循環，直到投影片放映中出現下一個聲音事件。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 指定滑鼠點擊是否會讓投影片前進。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 指定滑鼠點擊是否會讓投影片前進。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | 此屬性指定投影片放映是否會在特定時間後移動至下一張投影片。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 此屬性指定投影片放映是否會在特定時間後移動至下一張投影片。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 指定過渡應於多少毫秒後開始。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 指定過渡應於多少毫秒後開始。 |
| [getSpeed()](#getSpeed--) | 指定從目前投影片過渡到下一張投影片時使用的過渡速度。 |
| [setSpeed(int value)](#setSpeed-int-) | 指定從目前投影片過渡到下一張投影片時使用的過渡速度。 |
| [getValue()](#getValue--) | 投影片放映過渡值。 |
| [getType()](#getType--) | 過渡類型。 |
| [setType(int value)](#setType-int-) | 過渡類型。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 指定此聲音是否為內建聲音。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 指定此聲音是否為內建聲音。 |
| [getSoundName()](#getSoundName--) | 指定過渡聲音的人類可讀名稱。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 指定過渡聲音的人類可讀名稱。 |
| [getDuration()](#getDuration--) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |
| [setDuration(int value)](#setDuration-int-) | 取得或設定投影片過渡效果的持續時間（以毫秒為單位）。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 SlideShowTransition 實例是否相等。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式，適用於雜湊演算法與資料結構（如雜湊表）。 |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

返回或設定嵌入的音訊資料。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**返回：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

返回或設定嵌入的音訊資料。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

設定或返回投影片過渡的聲音模式。可讀寫 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**返回：**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

設定或返回投影片過渡的聲音模式。可讀寫 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

此屬性指定聲音是否會持續循環，直到投影片放映中出現下一個聲音事件。可讀寫布林。

**返回：**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

此屬性指定聲音是否會持續循環，直到投影片放映中出現下一個聲音事件。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

指定滑鼠點擊是否會讓投影片前進。若未指定此屬性，預設為 true。可讀寫布林。

**返回：**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

指定滑鼠點擊是否會讓投影片前進。若未指定此屬性，預設為 true。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

此屬性指定投影片放映是否會在特定時間後移動至下一張投影片。可讀寫布林。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一個投影片過渡
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


**返回：**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

此屬性指定投影片放映是否會在特定時間後移動至下一張投影片。可讀寫布林。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 取得第一個投影片過渡
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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

指定過渡應於多少毫秒後開始。此設定可與 advClick 屬性結合使用。若未指定此屬性，則視為不會自動前進。可讀寫 long。

**返回：**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

指定過渡應於多少毫秒後開始。此設定可與 advClick 屬性結合使用。若未指定此屬性，則視為不會自動前進。可讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

指定從目前投影片過渡到下一張投影片時使用的過渡速度。可讀寫 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**返回：**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

指定從目前投影片過渡到下一張投影片時使用的過渡速度。可讀寫 [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

投影片放映過渡值。唯讀 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**返回：**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

過渡類型。可讀寫 [TransitionType](../../com.aspose.slides/transitiontype)。

**返回：**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

過渡類型。可讀寫 [TransitionType](../../com.aspose.slides/transitiontype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

指定此聲音是否為內建聲音。若此屬性設為 true，則產生應用程式會檢查此聲音的 name 屬性是否在其內建聲音清單中，並可依需求顯示自訂名稱或 UI。可讀寫布林。

**返回：**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

指定此聲音是否為內建聲音。若此屬性設為 true，則產生應用程式會檢查此聲音的 name 屬性是否在其內建聲音清單中，並可依需求顯示自訂名稱或 UI。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

指定過渡聲音的人類可讀名稱。必須先指派 Sound（\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)）屬性才能取得或設定聲音名稱。可讀寫 String。

**返回：**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

指定過渡聲音的人類可讀名稱。必須先指派 Sound（\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)）屬性才能取得或設定聲音名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

取得或設定投影片過渡效果的持續時間（以毫秒為單位）。可讀寫 int。

--------------------

相當於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性與過渡類型自動決定持續時間。

**返回：**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

設定投影片過渡效果的持續時間（以毫秒為單位）。可讀寫 int。

--------------------

相當於 PresentationML 架構中 p:transition 元素的 p14:dur 屬性。若未設定，則會根據 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 屬性與過渡類型自動決定持續時間。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 SlideShowTransition 實例是否相等。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前的 SlideShowTransition 比較的實例。 |

**返回：**
boolean -  **true**  若指定的 SlideShowTransition 與目前的相等；否則 **false** 。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式，適用於雜湊演算法與資料結構（如雜湊表）。

**返回：**
int - 23454

--------------------

為使編譯器快樂而覆寫。因物件可變，始終返回常數。