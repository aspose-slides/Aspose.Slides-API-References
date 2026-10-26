---
title: Effect
second_title: Aspose.Slides for Android 透過 Java API 參考文件
description: 表示動畫效果。
type: docs
url: /zh-hant/com.aspose.slides/effect/
---
**繼承:**  
java.lang.Object

**所有已實作的介面：**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

表示動畫效果。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSequence()](#getSequence--) | 傳回效果的序列。 |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 唯讀 [ITextAnimation](../../com.aspose.slides/itextanimation)。 |
| [getPresetClassType()](#getPresetClassType--) | 定義效果的類別。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 定義效果的類別。 |
| [getType()](#getType--) | 定義效果的類型。 |
| [setType(int value)](#setType-int-) | 定義效果的類型。 |
| [getSubtype()](#getSubtype--) | 定義效果的子類型。 |
| [setSubtype(int value)](#setSubtype-int-) | 定義效果的子類型。 |
| [getBehaviors()](#getBehaviors--) | 傳回效果的行為集合。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 傳回效果的行為集合。 |
| [getTiming()](#getTiming--) | 定義效果的時間值。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 定義效果的時間值。 |
| [getTargetShape()](#getTargetShape--) | 傳回效果的目標形狀。 |
| [getSound()](#getSound--) | 已定義效果的嵌入音效。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 已定義效果的嵌入音效。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | 此屬性指定動畫效果是否停止先前的音效。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 此屬性指定動畫效果是否停止先前的音效。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 定義效果的後續動畫類型。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 定義效果的後續動畫類型。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 定義效果的後續動畫顏色。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 定義效果的後續動畫顏色。 |
| [getAnimateTextType()](#getAnimateTextType--) | 定義效果的文字動畫類型。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 定義效果的文字動畫類型。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 定義動畫文字部份（單詞或字母）之間的延遲。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 定義動畫文字部份（單詞或字母）之間的延遲。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

傳回效果的序列。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**傳回：**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation 唯讀 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**傳回：**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

定義效果的類別。可讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**傳回：**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

定義效果的類別。可讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

定義效果的類型。可讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**傳回：**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

定義效果的類型。可讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

定義效果的子類型。可讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**傳回：**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

定義效果的子類型。可讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

傳回效果的行為集合。可讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**傳回：**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

傳回效果的行為集合。可讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

定義效果的時間值。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**傳回：**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

定義效果的時間值。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

傳回效果的目標形狀。唯讀 [IShape](../../com.aspose.slides/ishape)。

**傳回：**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

已定義效果的嵌入音效。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 獲取投影片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 以位元組陣列提取效果音效
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**傳回：**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

已定義效果的嵌入音效。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 獲取投影片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 以位元組陣列提取效果音效
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

此屬性指定動畫效果是否停止先前的音效。可讀寫  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 取得第二張投影片的第一個效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 將第二個效果的增強/音效更改為「Stop Previous Sound」
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回：**  
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

此屬性指定動畫效果是否停止先前的音效。可讀寫  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 取得第二張投影片的第一個效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 將第二個效果的增強/音效更改為 "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

定義效果的後續動畫類型。可讀寫 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 After animation 更改為 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**  
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

定義效果的後續動畫類型。可讀寫 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 After animation 更改為 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

定義效果的後續動畫顏色。可讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 After animation 類型更改為「Color」
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果 After animation 顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

定義效果的後續動畫顏色。可讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 After animation 類型更改為「Color」
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果 After animation 顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

定義效果的文字動畫類型。形狀文字可以按字母、按單詞或一次性全部動畫化。可讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 Animate text 類型更改為 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**  
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

定義效果的文字動畫類型。形狀文字可以按字母、按單詞或一次性全部動畫化。可讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 Animate text 類型更改為 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

定義動畫文字部份（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。可讀寫  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 Animate text 類型更改為 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 設定動畫文字部份之間的延遲為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**  
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

定義動畫文字部份（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。可讀寫  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果 Animate text 類型更改為 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 設定動畫文字部份之間的延遲為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**  
com.aspose.slides.IDOMObject