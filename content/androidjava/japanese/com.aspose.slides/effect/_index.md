---
title: Effect
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: アニメーション効果を表します。
type: docs
url: /ja/com.aspose.slides/effect/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

アニメーション効果を表します。
## Methods

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | エフェクトのシーケンスを返します。 |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 読み取り専用 [ITextAnimation](../../com.aspose.slides/itextanimation)。 |
| [getPresetClassType()](#getPresetClassType--) | エフェクトのクラスを定義します。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | エフェクトのクラスを定義します。 |
| [getType()](#getType--) | エフェクトの種類を定義します。 |
| [setType(int value)](#setType-int-) | エフェクトの種類を定義します。 |
| [getSubtype()](#getSubtype--) | エフェクトのサブタイプを定義します。 |
| [setSubtype(int value)](#setSubtype-int-) | エフェクトのサブタイプを定義します。 |
| [getBehaviors()](#getBehaviors--) | エフェクトのビヘイビアのコレクションを返します。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | エフェクトのビヘイビアのコレクションを返します。 |
| [getTiming()](#getTiming--) | エフェクトのタイミング値を定義します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | エフェクトのタイミング値を定義します。 |
| [getTargetShape()](#getTargetShape--) | エフェクトの対象シェイプを返します。 |
| [getSound()](#getSound--) | エフェクトの埋め込みサウンドを定義します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | エフェクトの埋め込みサウンドを定義します。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | エフェクトの後のアニメーションタイプを定義します。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | エフェクトの後のアニメーションタイプを定義します。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | エフェクトの後のアニメーションカラーを定義します。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | エフェクトの後のアニメーションカラーを定義します。 |
| [getAnimateTextType()](#getAnimateTextType--) | エフェクトのテキストアニメーションタイプを定義します。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | エフェクトのテキストアニメーションタイプを定義します。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | アニメーション化されたテキストパート（単語または文字）間の遅延を定義します。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | アニメーション化されたテキストパート（単語または文字）間の遅延を定義します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

エフェクトのシーケンスを返します。読み取り専用 [ISequence](../../com.aspose.slides/isequence)。

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation 読み取り専用 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**戻り値:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

エフェクトのクラスを定義します。読み取り/書き込み [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**戻り値:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

エフェクトのクラスを定義します。読み取り/書き込み [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

エフェクトの種類を定義します。読み取り/書き込み [EffectType](../../com.aspose.slides/effecttype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

エフェクトの種類を定義します。読み取り/書き込み [EffectType](../../com.aspose.slides/effecttype)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

エフェクトのサブタイプを定義します。読み取り/書き込み [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**戻り値:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

エフェクトのサブタイプを定義します。読み取り/書き込み [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

エフェクトのビヘイビアのコレクションを返します。読み取り/書き込み [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**戻り値:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

エフェクトのビヘイビアのコレクションを返します。読み取り/書き込み [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

エフェクトのタイミング値を定義します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

エフェクトのタイミング値を定義します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

エフェクトの対象シェイプを返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

エフェクトの埋め込みサウンドを定義します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // スライドのエフェクトシーケンスを取得します
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // エフェクトのサウンドをバイト配列として抽出します
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

エフェクトの埋め込みサウンドを定義します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // スライドのエフェクトシーケンスを取得します
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // エフェクトのサウンドをバイト配列として抽出します
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り/書き込み boolean 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 2番目のスライドの最初のエフェクトを取得します。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 2番目のエフェクトの拡張機能/サウンドを「Stop Previous Sound」に変更します。
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**戻り値:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り/書き込み boolean 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 2番目のスライドの最初のエフェクトを取得します。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 2番目のエフェクトの拡張機能/サウンドを「Stop Previous Sound」に変更します。
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

エフェクトの後のアニメーションタイプを定義します。読み取り/書き込み [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの After animation を "Hide on Next Mouse Click" に変更します。
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

エフェクトの後のアニメーションタイプを定義します。読み取り/書き込み [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの After animation を "Hide on Next Mouse Click" に変更します。
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

エフェクトの後のアニメーションカラーを定義します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの After animation タイプを "Color" に変更します。
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // エフェクトの After animation カラーを設定します。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

エフェクトの後のアニメーションカラーを定義します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの After animation タイプを "Color" に変更します。
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // エフェクトの After animation カラーを設定します。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

エフェクトのテキストアニメーションタイプを定義します。シェイプのテキストは文字単位、単語単位、または一括でアニメーション化できます。読み取り/書き込み AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの Animate text タイプを "By letter" に変更します。
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**戻り値:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

エフェクトのテキストアニメーションタイプを定義します。シェイプのテキストは文字単位、単語単位、または一括でアニメーション化できます。読み取り/書き込み AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの Animate text タイプを "By letter" に変更します。
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

アニメーション化されたテキストパート（単語または文字）間の遅延を定義します。正の値はエフェクト期間の割合を指定し、負の値は秒単位の遅延を指定します。読み取り/書き込み float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの Animate text タイプを "By word" に変更します。
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーション化されたテキストパーツ間の遅延をエフェクト期間の 20% に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

アニメーション化されたテキストパート（単語または文字）間の遅延を定義します。正の値はエフェクト期間の割合を指定し、負の値は秒単位の遅延を指定します。読み取り/書き込み float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの Animate text タイプを "By word" に変更します。
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーション化されたテキストパーツ間の遅延をエフェクト期間の 20% に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject