---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /zh-hant/com.aspose.slides/ieffect/
---```
public interface IEffect
```

表示動畫效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSequence()](#getSequence--) | 傳回效果的序列。 |
| [getTextAnimation()](#getTextAnimation--) | 傳回文字動畫。 |
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
| [getSound()](#getSound--) | 為效果定義內嵌聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 為效果定義內嵌聲音。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | 此屬性指定動畫效果是否停止先前的聲音。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 此屬性指定動畫效果是否停止先前的聲音。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 為效果定義後續動畫類型。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 為效果定義後續動畫類型。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 為效果定義後續動畫顏色。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 為效果定義後續動畫顏色。 |
| [getAnimateTextType()](#getAnimateTextType--) | 為效果定義文字動畫類型。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 為效果定義文字動畫類型。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 定義動畫文字部件（字或詞）之間的延遲。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 定義動畫文字部件（字或詞）之間的延遲。 |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

傳回效果的序列。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**傳回值:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

傳回文字動畫。唯讀 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**傳回值:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

定義效果的類別。可讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**傳回值:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

定義效果的類別。可讀寫 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

定義效果的類型。可讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**傳回值:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

定義效果的類型。可讀寫 [EffectType](../../com.aspose.slides/effecttype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

定義效果的子類型。可讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**傳回值:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

定義效果的子類型。可讀寫 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

傳回效果的行為集合。可讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**傳回值:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

傳回效果的行為集合。可讀寫 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

定義效果的時間值。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**傳回值:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

定義效果的時間值。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

傳回效果的目標形狀。唯讀 [IShape](../../com.aspose.slides/ishape)。

**傳回值:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

為效果定義內嵌聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回值:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

為效果定義內嵌聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

此屬性指定動畫效果是否停止先前的聲音。可讀寫  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 取得第二張幻燈片的第一個效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 將第二個效果的增強/聲音變更為「停止先前的聲音」
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回值:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

此屬性指定動畫效果是否停止先前的聲音。可讀寫  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 取得第二張幻燈片的第一個效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 將第二個效果的增強/聲音變更為「停止先前的聲音」
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

為效果定義後續動畫類型。可讀寫  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後續動畫變更為「在下一次滑鼠點擊時隱藏」
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回值:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

為效果定義後續動畫類型。可讀寫  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後續動畫變更為「在下一次滑鼠點擊時隱藏」
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

為效果定義後續動畫顏色。可讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後續動畫類型變更為 "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果的後續動畫顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

為效果定義後續動畫顏色。可讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的後續動畫類型變更為 "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 設定效果的後續動畫顏色。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

為效果定義文字動畫類型。形狀文字可依字母、單字或一次全部進行動畫。可讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型變更為「按字母」
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回值:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

為效果定義文字動畫類型。形狀文字可依字母、單字或一次全部進行動畫。可讀寫  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型變更為「按字母」
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

定義動畫文字部件（字或詞）之間的延遲。正值表示效果持續時間的百分比。負值表示以秒為單位的延遲。可讀寫  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型變更為「按詞」
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 將動畫文字部件之間的延遲設定為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> 
```

**傳回值:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

定義動畫文字部件（字或詞）之間的延遲。正值表示效果持續時間的百分比。負值表示以秒為單位的延遲。可讀寫  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 取得第一張幻燈片的第一個效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 將效果的動畫文字類型變更為「按詞」
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 將動畫文字部件之間的延遲設定為效果持續時間的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |