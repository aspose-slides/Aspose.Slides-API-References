---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: アニメーション効果を表します。
type: docs
url: /ja/com.aspose.slides/ieffect/
---```
public interface IEffect
```

アニメーション効果を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSequence()](#getSequence--) | エフェクトのシーケンスを返します。 |
| [getTextAnimation()](#getTextAnimation--) | テキストアニメーションを返します。 |
| [getPresetClassType()](#getPresetClassType--) | エフェクトのクラスを定義します。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | エフェクトのクラスを定義します。 |
| [getType()](#getType--) | エフェクトのタイプを定義します。 |
| [setType(int value)](#setType-int-) | エフェクトのタイプを定義します。 |
| [getSubtype()](#getSubtype--) | エフェクトのサブタイプを定義します。 |
| [setSubtype(int value)](#setSubtype-int-) | エフェクトのサブタイプを定義します。 |
| [getBehaviors()](#getBehaviors--) | エフェクトのビヘイビアコレクションを返します。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | エフェクトのビヘイビアコレクションを返します。 |
| [getTiming()](#getTiming--) | エフェクトのタイミング値を定義します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | エフェクトのタイミング値を定義します。 |
| [getTargetShape()](#getTargetShape--) | エフェクトの対象シェイプを返します。 |
| [getSound()](#getSound--) | エフェクトの埋め込みサウンドを定義します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | エフェクトの埋め込みサウンドを定義します。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | エフェクトのアフターアニメーションタイプを定義します。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | エフェクトのアフターアニメーションタイプを定義します。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | エフェクトのアフターアニメーションカラーを定義します。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | エフェクトのアフターアニメーションカラーを定義します。 |
| [getAnimateTextType()](#getAnimateTextType--) | エフェクトのアニメートテキストタイプを定義します。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | エフェクトのアニメートテキストタイプを定義します。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | アニメーションテキストパーツ（単語または文字）間の遅延を定義します。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | アニメーションテキストパーツ（単語または文字）間の遅延を定義します。 |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


エフェクトのシーケンスを返します。読み取り専用 [ISequence](../../com.aspose.slides/isequence)。

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


テキストアニメーションを返します。読み取り専用 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**戻り値:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


エフェクトのクラスを定義します。読み取り/書き込み [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**戻り値:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


エフェクトのクラスを定義します。読み取り/書き込み [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


エフェクトのタイプを定義します。読み取り/書き込み [EffectType](../../com.aspose.slides/effecttype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


エフェクトのタイプを定義します。読み取り/書き込み [EffectType](../../com.aspose.slides/effecttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


エフェクトのサブタイプを定義します。読み取り/書き込み [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**戻り値:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


エフェクトのサブタイプを定義します。読み取り/書き込み [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


エフェクトのビヘイビアコレクションを返します。読み取り/書き込み [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**戻り値:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


エフェクトのビヘイビアコレクションを返します。読み取り/書き込み [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


エフェクトのタイミング値を定義します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


エフェクトのタイミング値を定義します。読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


エフェクトの対象シェイプを返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public abstract IAudio getSound()
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
public abstract void setSound(IAudio value)
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り/書き込み  boolean 。

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
>          // 2番目のエフェクトのエンハンスメント/サウンドを「前のサウンドを停止」に変更します
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
public abstract void setStopPreviousSound(boolean value)
```


この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み取り/書き込み  boolean 。

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
>          // 2番目のエフェクトのエンハンスメント/サウンドを「前のサウンドを停止」に変更します
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


エフェクトのアフターアニメーションタイプを定義します。読み取り/書き込み  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアフターアニメーションを「次のマウスクリックで非表示」に変更します
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


エフェクトのアフターアニメーションタイプを定義します。読み取り/書き込み  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアフターアニメーションを「次のマウスクリックで非表示」に変更します
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


エフェクトのアフターアニメーションカラーを定義します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアフターアニメーションタイプを「Color」に変更します
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // エフェクトのアフターアニメーションカラーを設定します。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


エフェクトのアフターアニメーションカラーを定義します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアフターアニメーションタイプを「Color」に変更します
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // エフェクトのアフターアニメーションカラーを設定します。
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


エフェクトのアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、または一括でアニメーションできます。読み取り/書き込み  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを「文字単位」に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


エフェクトのアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、または一括でアニメーションできます。読み取り/書き込み  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを「文字単位」に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


アニメーションテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの期間のパーセンテージを指定し、負の値は秒単位の遅延を指定します。読み取り/書き込み  float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを「単語単位」に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーションテキストパーツ間の遅延をエフェクトの期間の20%に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


アニメーションテキストパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの期間のパーセンテージを指定し、負の値は秒単位の遅延を指定します。読み取り/書き込み  float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを「単語単位」に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーションテキストパーツ間の遅延をエフェクトの期間の20%に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |