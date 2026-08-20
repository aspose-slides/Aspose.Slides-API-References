---
title: Effect
second_title: Aspose.Slides for Java API 參考
description: 代表動畫效果。
type: docs
url: /zh-hant/com.aspose.slides/effect/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

表示動畫效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSequence()](#getSequence--) | 返回效果的序列。 |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 唯讀 [ITextAnimation](../../com.aspose.slides/itextanimation)。 |
| [getPresetClassType()](#getPresetClassType--) | 定義效果的類別。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 定義效果的類別。 |
| [getType()](#getType--) | 定義效果的類型。 |
| [setType(int value)](#setType-int-) | 定義效果的類型。 |
| [getSubtype()](#getSubtype--) | 定義效果的子類型。 |
| [setSubtype(int value)](#setSubtype-int-) | 定義效果的子類型。 |
| [getBehaviors()](#getBehaviors--) | 返回效果的行為集合。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 返回效果的行為集合。 |
| [getTiming()](#getTiming--) | 定義效果的時間值。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 定義效果的時間值。 |
| [getTargetShape()](#getTargetShape--) | 返回效果的目標形狀。 |
| [getSound()](#getSound--) | 已定義效果的嵌入聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 已定義效果的嵌入聲音。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | 此屬性指定動畫效果是否停止先前的聲音。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 此屬性指定動畫效果是否停止先前的聲音。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 定義效果的後置動畫類型。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 定義效果的後置動畫類型。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 定義效果的後置動畫顏色。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 定義效果的後置動畫顏色。 |
| [getAnimateTextType()](#getAnimateTextType--) | 定義效果的文字動畫類型。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 定義效果的文字動畫類型。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 定義動畫文字部分（單詞或字母）之間的延遲。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 定義動畫文字部分（單詞或字母）之間的延遲。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

返回效果的序列。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**返回：**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation 唯讀 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**返回：**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

定義效果的類別。讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**返回：**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

定義效果的類別。讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

定義效果的類型。讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**返回：**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

定義效果的類型。讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

定義效果的子類型。讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**返回：**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

定義效果的子類型。讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

返回效果的行為集合。讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**返回：**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

返回效果的行為集合。讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

定義效果的時間值。讀寫 [ITiming](../../com.aspose.slides/itiming)。

**返回：**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

定義效果的時間值。讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

返回效果的目標形狀。唯讀 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

已定義效果的嵌入聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 取得投影片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 以位元組陣列提取效果聲音
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

已定義效果的嵌入聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 取得投影片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 以位元組陣列提取效果聲音
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

此屬性指定動畫效果是否停止先前的聲音。讀寫  boolean .

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
>          // 將第二個效果的增強/聲音更改為 "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

此屬性指定動畫效果是否停止先前的聲音。讀寫  boolean .

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
>          // 將第二個效果的增強/聲音更改為 "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

定義效果的後置動畫類型。讀寫 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後置動畫更改為 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

定義效果的後置動畫類型。讀寫 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後置動畫更改為 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

定義效果的後置動畫顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後置動畫類型更改為 "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果的後置動畫顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

定義效果的後置動畫顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後置動畫類型更改為 "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果的後置動畫顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

定義效果的文字動畫類型。形狀文字可以按字母、按單詞或一次性全部動畫。讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型更改為 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

定義效果的文字動畫類型。形狀文字可以按字母、按單詞或一次性全部動畫。讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型更改為 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

定義動畫文字部分（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。讀寫  float .

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型更改為 "By word"
> 
>      // 將動畫文字部分之間的延遲設定為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

定義動畫文字部分（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。讀寫  float .

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張投影片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型更改為 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 將動畫文字部分之間的延遲設定為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject