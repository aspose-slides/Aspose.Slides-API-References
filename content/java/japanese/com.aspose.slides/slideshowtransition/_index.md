---
title: SlideShowTransition
second_title: Aspose.Slides for Java API リファレンス
description: スライドショーのトランジションを表します。
type: docs
url: /ja/com.aspose.slides/slideshowtransition/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

スライドショーのトランジションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSound()](#getSound--) | 埋め込みオーディオデータを取得または設定します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 埋め込みオーディオデータを取得または設定します。 |
| [getSoundMode()](#getSoundMode--) | スライドトランジションのサウンドモードを設定または取得します。 |
| [setSoundMode(int value)](#setSoundMode-int-) | スライドトランジションのサウンドモードを設定または取得します。 |
| [getSoundLoop()](#getSoundLoop--) | この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | マウスクリックでスライドを進めるかどうかを指定します。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | マウスクリックでスライドを進めるかどうかを指定します。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | トランジションが開始すべき時間（ミリ秒）を指定します。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | トランジションが開始すべき時間（ミリ秒）を指定します。 |
| [getSpeed()](#getSpeed--) | 現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。 |
| [setSpeed(int value)](#setSpeed-int-) | 現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。 |
| [getValue()](#getValue--) | スライドショーのトランジション値です。 |
| [getType()](#getType--) | トランジションのタイプです。 |
| [setType(int value)](#setType-int-) | トランジションのタイプです。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [getSoundName()](#getSoundName--) | トランジションのサウンドの人が読みやすい名前を指定します。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | トランジションのサウンドの人が読みやすい名前を指定します。 |
| [getDuration()](#getDuration--) | スライドトランジション効果の継続時間をミリ秒単位で取得または設定します。 |
| [setDuration(int value)](#setDuration-int-) | スライドトランジション効果の継続時間をミリ秒単位で取得または設定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2つの SlideShowTransition インスタンスが等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定のタイプに対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルのようなデータ構造で使用できます。 |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

埋め込みオーディオデータを取得または設定します。読み書き [IAudio](../../com.aspose.slides/iaudio)。

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

埋め込みオーディオデータを取得または設定します。読み書き [IAudio](../../com.aspose.slides/iaudio)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

スライドトランジションのサウンドモードを設定または取得します。読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**戻り値:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

スライドトランジションのサウンドモードを設定または取得します。読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。読み書き boolean。

**戻り値:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。読み書き boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が想定されます。読み書き boolean。

**戻り値:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が想定されます。読み書き boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライド トランジションを取得
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After フラグがチェックされているか確認
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time の値を取得
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライド トランジションを取得
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After フラグがチェックされているか確認
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time の値を取得
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

トランジションが開始すべき時間（ミリ秒）を指定します。この設定は advClick 属性と組み合わせて使用できます。この属性が指定されていない場合、自動的に進むことはありません。読み書き long。

**戻り値:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

トランジションが開始すべき時間（ミリ秒）を指定します。この設定は advClick 属性と組み合わせて使用できます。この属性が指定されていない場合、自動的に進むことはありません。読み書き long。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

スライドトランジションの速度を設定または取得します。読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**戻り値:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

スライドトランジションの速度を設定または取得します。読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

スライドショーのトランジション値です。読み取り専用 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**戻り値:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

トランジションのタイプです。読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

トランジションのタイプです。読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンド一覧でこのサウンドに指定された name 属性をチェックし、必要に応じてカスタム名や UI を表示できます。読み書き boolean。

**戻り値:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンド一覧でこのサウンドに指定された name 属性をチェックし、必要に応じてカスタム名や UI を表示できます。読み書き boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

トランジションのサウンドの人が読みやすい名前を指定します。Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) プロパティに割り当ててサウンド名を取得または設定する必要があります。読み書き String。

**戻り値:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

トランジションのサウンドの人が読みやすい名前を指定します。Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) プロパティに割り当ててサウンド名を取得または設定する必要があります。読み書き String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

スライドトランジション効果の継続時間をミリ秒単位で取得または設定します。読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。設定されていない場合、継続時間は \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) プロパティとトランジションタイプに基づいて自動的に決定されます。

**戻り値:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

スライドトランジション効果の継続時間をミリ秒単位で取得または設定します。読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。設定されていない場合、継続時間は \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) プロパティとトランジションタイプに基づいて自動的に決定されます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

2つの SlideShowTransition インスタンスが等しいかどうかを判断します。読み書き boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 現在の SlideShowTransition と比較する SlideShowTransition。 |

**戻り値:**
boolean -  **true**  指定された SlideShowTransition が現在の SlideShowTransition と等しい場合; それ以外の場合は **false** 。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定のタイプに対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルのようなデータ構造で使用できます。

**戻り値:**
int - 23454

--------------------

コンパイラを満足させるためにオーバーライドしています。オブジェクトは可変であるため、常に定数を返します。