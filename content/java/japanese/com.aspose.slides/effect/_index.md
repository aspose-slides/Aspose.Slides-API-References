---
title: Effect
second_title: Aspose.Slides for Java API リファレンス
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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSequence()](#getSequence--) | 効果のシーケンスを返します。 |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 読み取り専用 [ITextAnimation](../../com.aspose.slides/itextanimation)。 |
| [getPresetClassType()](#getPresetClassType--) | 効果のクラスを定義します。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 効果のクラスを定義します。 |
| [getType()](#getType--) | 効果のタイプを定義します。 |
| [setType(int value)](#setType-int-) | 効果のタイプを定義します。 |
| [getSubtype()](#getSubtype--) | 効果のサブタイプを定義します。 |
| [setSubtype(int value)](#setSubtype-int-) | 効果のサブタイプを定義します。 |
| [getBehaviors()](#getBehaviors--) | 効果のビヘイビアのコレクションを返します。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 効果のビヘイビアのコレクションを返します。 |
| [getTiming()](#getTiming--) | 効果のタイミング値を定義します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 効果のタイミング値を定義します。 |
| [getTargetShape()](#getTargetShape--) | 効果の対象シェイプを返します。 |
| [getSound()](#getSound--) | 効果の埋め込みサウンドを定義します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 効果の埋め込みサウンドを定義します。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 効果の後のアニメーションタイプを定義します。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 効果の後のアニメーションタイプを定義します。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 効果の後のアニメーションカラーを定義します。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 効果の後のアニメーションカラーを定義します。 |
| [getAnimateTextType()](#getAnimateTextType--) | 効果のアニメートテキストタイプを定義します。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 効果のアニメートテキストタイプを定義します。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | アニメーションテキストのパーツ（単語または文字）間の遅延を定義します。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | アニメーションテキストのパーツ（単語または文字）間の遅延を定義します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

効果のシーケンスを返します。読み取り専用 [ISequence](../../com.aspose.slides/isequence)。

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

効果のクラスを定義します。読み書き可能 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**戻り値:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

効果のクラスを定義します。読み書き可能 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

効果のタイプを定義します。読み書き可能 [EffectType](../../com.aspose.slides/effecttype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

効果のタイプを定義します。読み書き可能 [EffectType](../../com.aspose.slides/effecttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

効果のサブタイプを定義します。読み書き可能 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**戻り値:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

効果のサブタイプを定義します。読み書き可能 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

効果のビヘイビアのコレクションを返します。読み書き可能 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**戻り値:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

効果のビヘイビアのコレクションを返します。読み書き可能 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

効果のタイミング値を定義します。読み書き可能 [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

効果のタイミング値を定義します。読み書き可能 [ITiming](../../com.aspose.slides/itiming)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

効果の対象シェイプを返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

効果の埋め込みサウンドを定義します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

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

効果の埋め込みサウンドを定義します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

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
public final boolean getStopPreviousSound()
```

この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み書き可能 boolean 。

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
>          // 2番目のエフェクトの拡張機能/サウンドを "Stop Previous Sound" に変更します
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

この属性は、アニメーション効果が前のサウンドを停止するかどうかを指定します。読み書き可能 boolean 。

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
>          // 2番目のエフェクトの拡張機能/サウンドを "Stop Previous Sound" に変更します
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
public final int getAfterAnimationType()
```

効果の後のアニメーションタイプを定義します。読み書き可能 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのAfter animationを "Hide on Next Mouse Click" に変更します
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

効果の後のアニメーションタイプを定義します。読み書き可能 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのAfter animationを "Hide on Next Mouse Click" に変更します
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
public final IColorFormat getAfterAnimationColor()
```

効果の後のアニメーションカラーを定義します。読み書き可能 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのAfter animationタイプを "Color" に変更します
> 
>      // エフェクトのAfter animationカラーを設定します。
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
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

効果の後のアニメーションカラーを定義します。読み書き可能 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのAfter animationタイプを "Color" に変更します
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // エフェクトのAfter animationカラーを設定します。
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
public final int getAnimateTextType()
```

効果のアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて同時にアニメーション化できます。読み書き可能 AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを "By letter" に変更します
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

効果のアニメートテキストタイプを定義します。シェイプのテキストは文字単位、単語単位、またはすべて同時にアニメーション化できます。読み書き可能 AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを "By letter" に変更します
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
public final float getDelayBetweenTextParts()
```

アニメーションテキストのパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの継続時間の割合を指定します。負の値は秒単位の遅延を指定します。読み書き可能 float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを "By word" に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーションテキストのパーツ間の遅延をエフェクト継続時間の20%に設定します。
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

アニメーションテキストのパーツ（単語または文字）間の遅延を定義します。正の値はエフェクトの継続時間の割合を指定します。負の値は秒単位の遅延を指定します。読み書き可能 float 。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 最初のスライドの最初のエフェクトを取得します。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // エフェクトのアニメートテキストタイプを "By word" に変更します
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // アニメーションテキストのパーツ間の遅延をエフェクト継続時間の20%に設定します。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent\_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject