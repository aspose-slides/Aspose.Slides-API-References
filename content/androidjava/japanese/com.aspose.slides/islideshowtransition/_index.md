---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /ja/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
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
| [getAdvanceAfter()](#getAdvanceAfter--) | スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | トランジションが開始されるまでの時間（ミリ秒）を指定します。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | トランジションが開始されるまでの時間（ミリ秒）を指定します。 |
| [getSpeed()](#getSpeed--) | 現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。 |
| [setSpeed(int value)](#setSpeed-int-) | 現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。 |
| [getValue()](#getValue--) | スライドショートランジションの値です。 |
| [getType()](#getType--) | トランジションの種類です。 |
| [setType(int value)](#setType-int-) | トランジションの種類です。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [getSoundName()](#getSoundName--) | トランジションのサウンドに対する人が読みやすい名前を指定します。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | トランジションのサウンドに対する人が読みやすい名前を指定します。 |
| [getDuration()](#getDuration--) | スライドトランジション効果の継続時間（ミリ秒）を取得または設定します。 |
| [setDuration(int value)](#setDuration-int-) | スライドトランジション効果の継続時間（ミリ秒）を取得または設定します。 |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

埋め込みオーディオデータを取得または設定します。読み書き [IAudio](../../com.aspose.slides/iaudio)。

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

埋め込みオーディオデータを取得または設定します。読み書き [IAudio](../../com.aspose.slides/iaudio)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

スライドトランジションのサウンドモードを設定または取得します。読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**戻り値:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

スライドトランジションのサウンドモードを設定または取得します。読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。読み書き boolean。

**戻り値:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が想定されます。読み書き boolean。

**戻り値:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が想定されます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドのトランジションを取得
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
public abstract void setAdvanceAfter(boolean value)
```

この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライドのトランジションを取得
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

トランジションが開始されるまでの時間（ミリ秒）を指定します。この設定は advClick 属性と併用できます。この属性が指定されていない場合、自動進行は行われないとみなされます。読み書き long。

**戻り値:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

トランジションが開始されるまでの時間（ミリ秒）を指定します。この設定は advClick 属性と併用できます。この属性が指定されていない場合、自動進行は行われないとみなされます。読み書き long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**戻り値:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

現在のスライドから次のスライドへ遷移する際に使用されるトランジション速度を指定します。読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

スライドショーのトランジション値です。読み取り専用 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**戻り値:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

トランジションの種類です。読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**戻り値:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

トランジションの種類です。読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストで指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。読み書き boolean。

**戻り値:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストで指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

トランジションのサウンドに対する人が読みやすい名前を指定します。(#getSound.getSound/#setSound(IAudio).setSound(IAudio)) プロパティに代入してサウンド名を取得または設定します。読み書き String。

**戻り値:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

トランジションのサウンドに対する人が読みやすい名前を指定します。\#getSound.getSound/#setSound(IAudio).setSound(IAudio) プロパティに代入してサウンド名を取得または設定します。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

スライドトランジション効果の継続時間（ミリ秒）を取得または設定します。読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。設定されていない場合、継続時間は \#getSpeed.getSpeed/#setSpeed(int).setSpeed(int) プロパティとトランジションタイプに基づいて自動的に決定されます。

**戻り値:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

スライドトランジション効果の継続時間（ミリ秒）を取得または設定します。読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。設定されていない場合、継続時間は \#getSpeed.getSpeed/#setSpeed(int).setSpeed(int) プロパティとトランジションタイプに基づいて自動的に決定されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |