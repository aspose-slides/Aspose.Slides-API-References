---
title: IEffect
second_title: Aspose.Slides の Java API リファレンス
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
| [getSequence()](#getSequence--) | 効果のシーケンスを返します。 |
| [getTextAnimation()](#getTextAnimation--) | テキストアニメーションを返します。 |
| [getPresetClassType()](#getPresetClassType--) | 効果のクラスを定義します。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 効果のクラスを定義します。 |
| [getType()](#getType--) | 効果のタイプを定義します。 |
| [setType(int value)](#setType-int-) | 効果のタイプを定義します。 |
| [getSubtype()](#getSubtype--) | 効果のサブタイプを定義します。 |
| [setSubtype(int value)](#setSubtype-int-) | 効果のサブタイプを定義します。 |
| [getBehaviors()](#getBehaviors--) | 効果の動作コレクションを返します。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 効果の動作コレクションを返します。 |
| [getTiming()](#getTiming--) | 効果のタイミング値を定義します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 効果のタイミング値を定義します。 |
| [getTargetShape()](#getTargetShape--) | 効果の対象シェイプを返します。 |
| [getSound()](#getSound--) | 効果の埋め込みサウンドを定義します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 効果の埋め込みサウンドを定義します。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | この属性はアニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | この属性はアニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 効果の後続アニメーションタイプを定義します。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 効果の後続アニメーションタイプを定義します。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 効果の後続アニメーションカラーを定義します。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 効果の後続アニメーションカラーを定義します。 |
| [getAnimateTextType()](#getAnimateTextType--) | 効果のアニメートテキストタイプを定義します。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 効果のアニメートテキストタイプを定義します。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | アニメーション化されたテキスト部分（単語または文字）間の遅延を定義します。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | アニメーション化されたテキスト部分（単語または文字）間の遅延を定義します。 |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


効果のシーケンスを返します。 読み取り専用 [ISequence](../../com.aspose.slides/isequence).

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


テキストアニメーションを返します。 読み取り専用 [ITextAnimation](../../com.aspose.slides/itextanimation).

**戻り値:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


効果のクラスを定義します。 読み書き [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**戻り値:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


効果のクラスを定義します。 読み書き [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


効果のタイプを定義します。 読み書き [EffectType](../../com.aspose.slides/effecttype).

**戻り値:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


効果のタイプを定義します。 読み書き [EffectType](../../com.aspose.slides/effecttype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


効果のサブタイプを定義します。 読み書き [EffectSubtype](../../com.aspose.slides/effectsubtype).

**戻り値:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


効果のサブタイプを定義します。 読み書き [EffectSubtype](../../com.aspose.slides/effectsubtype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


効果の動作コレクションを返します。 読み書き [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**戻り値:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


効果の動作コレクションを返します。 読み書き [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


効果のタイミング値を定義します。 読み書き [ITiming](../../com.aspose.slides/itiming).

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


効果のタイミング値を定義します。 読み書き [ITiming](../../com.aspose.slides/itiming).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


対象シェイプを返します。 読み取り専用 [IShape](../../com.aspose.slides/ishape).

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


効果の埋め込みサウンドを定義します。 読み書き [IAudio](../../com.aspose.slides/iaudio).

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
>          // エフェクトサウンドをバイト配列として抽出します
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


効果の埋め込みサウンドを定義します。 読み書き [IAudio](../../com.aspose.slides/iaudio).

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
>          // エフェクトサウンドをバイト配列として抽出します
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


この属性はアニメーション効果が前のサウンドを停止するかどうかを指定します。 読み書き  boolean .

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
>          // 2番目のエフェクトの「Enhancements/Sound」を「Stop Previous Sound」に変更します。
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


この属性はアニメーション効果が前のサウンドを停止するかどうかを指定します。 読み書き  boolean .

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
>          // 2番目のエフェクトの「Enhancements/Sound」を「Stop Previous Sound」に変更します。
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


効果の後続アニメーションタイプを定義します。 読み書き  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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
public abstract void setAfterAnimationType(int value)
```


効果の後続アニメーションタイプを定義します。 読み書き  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


効果の後続アニメーションカラーを定義します。 読み書き [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
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


効果の後続アニメーションカラーを定義します。 読み書き [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
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


効果のテキストアニメーションタイプを定義します。 シェイプのテキストは文字単位、単語単位、または一括でアニメーション化できます。 読み書き  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
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
public abstract void setAnimateTextType(int value)
```


効果のテキストアニメーションタイプを定義します。 シェイプのテキストは文字単位、単語単位、または一括でアニメーション化できます。 読み書き  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトの Animate text タイプを "By letter" に変更します。
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


アニメーション化されたテキスト部分（単語または文字）間の遅延を定義します。 正の値は効果の期間のパーセンテージを指定し、負の値は秒単位の遅延を指定します。 読み書き  float .

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
>      // アニメーション化されたテキスト部分間の遅延を効果の長さの 20% に設定します。
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


アニメーション化されたテキスト部分（単語または文字）間の遅延を定義します。 正の値は効果の期間のパーセンテージを指定し、負の値は秒単位の遅延を指定します。 読み書き  float .

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
>      // アニメーション化されたテキスト部分間の遅延を効果の期間の20%に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |