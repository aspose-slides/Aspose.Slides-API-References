---
title: SlideShowTransition
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: スライドショー遷移を表します。
type: docs
url: /ja/com.aspose.slides/slideshowtransition/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

スライドショー遷移を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSound()](#getSound--) | 埋め込みオーディオ データを取得または設定します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 埋め込みオーディオ データを取得または設定します。 |
| [getSoundMode()](#getSoundMode--) | スライド遷移のサウンドモードを設定または取得します。 |
| [setSoundMode(int value)](#setSoundMode-int-) | スライド遷移のサウンドモードを設定または取得します。 |
| [getSoundLoop()](#getSoundLoop--) | この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | マウスクリックでスライドを進めるかどうかを指定します。 |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | マウスクリックでスライドを進めるかどうかを指定します。 |
| [getAdvanceAfter()](#getAdvanceAfter--) | この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 遷移を開始すべきミリ秒単位の時間を指定します。 |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 遷移を開始すべきミリ秒単位の時間を指定します。 |
| [getSpeed()](#getSpeed--) | 現在のスライドから次のスライドへ遷移する際に使用する遷移速度を指定します。 |
| [setSpeed(int value)](#setSpeed-int-) | 現在のスライドから次のスライドへ遷移する際に使用する遷移速度を指定します。 |
| [getValue()](#getValue--) | スライドショー遷移の値です。 |
| [getType()](#getType--) | 遷移のタイプです。 |
| [setType(int value)](#setType-int-) | 遷移のタイプです。 |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | このサウンドが組み込みサウンドかどうかを指定します。 |
| [getSoundName()](#getSoundName--) | 遷移のサウンドの人間が読める名前を指定します。 |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 遷移のサウンドの人間が読める名前を指定します。 |
| [getDuration()](#getDuration--) | スライド遷移効果の持続時間をミリ秒単位で取得または設定します。 |
| [setDuration(int value)](#setDuration-int-) | スライド遷移効果の持続時間をミリ秒単位で取得または設定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2 つの SlideShowTransition インスタンスが等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能し、ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できます。 |
### getSound() {#getSound--}
```
public final IAudio getSound()
```


埋め込みオーディオ データを取得または設定します。 読み書き [IAudio](../../com.aspose.slides/iaudio)。

**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


埋め込みオーディオ データを取得または設定します。 読み書き [IAudio](../../com.aspose.slides/iaudio)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```


スライド遷移のサウンドモードを設定または取得します。 読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**戻り値:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```


スライド遷移のサウンドモードを設定または取得します。 読み書き [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```


この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 読み書き boolean。

**戻り値:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```


この属性は、スライドショーで次のサウンドイベントが発生するまでサウンドをループさせるかどうかを指定します。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```


マウスクリックでスライドを進めるかどうかを指定します。 この属性が指定されていない場合は true とみなされます。 読み書き boolean。

**戻り値:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```


マウスクリックでスライドを進めるかどうかを指定します。 この属性が指定されていない場合は true とみなされます。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```


この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライド遷移を取得
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


この属性は、一定時間後にスライドショーが次のスライドに移動するかどうかを指定します。 読み書き boolean。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 最初のスライド遷移を取得
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
public final long getAdvanceAfterTime()
```


遷移を開始すべきミリ秒単位の時間を指定します。 この設定は advClick 属性と組み合わせて使用できます。 この属性が指定されていない場合、自動的に進むことはありません。 読み書き long。

**戻り値:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```


遷移を開始すべきミリ秒単位の時間を指定します。 この設定は advClick 属性と組み合わせて使用できます。 この属性が指定されていない場合、自動的に進むことはありません。 読み書き long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```


現在のスライドから次のスライドへ遷移する際に使用する遷移速度を指定します。 読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**戻り値:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```


現在のスライドから次のスライドへ遷移する際に使用する遷移速度を指定します。 読み書き [TransitionSpeed](../../com.aspose.slides/transitionspeed)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```


スライドショー遷移の値です。 読み取り専用 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)。

**戻り値:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```


遷移のタイプです。 読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**戻り値:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


遷移のタイプです。 読み書き [TransitionType](../../com.aspose.slides/transitiontype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```


このサウンドが組み込みサウンドかどうかを指定します。 この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストでこのサウンドに指定された name 属性をチェックし、必要に応じてカスタム名や UI を表示できます。 読み書き boolean。

**戻り値:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```


このサウンドが組み込みサウンドかどうかを指定します。 この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストでこのサウンドに指定された name 属性をチェックし、必要に応じてカスタム名や UI を表示できます。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```


遷移のサウンドの人間が読める名前を指定します。 Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) プロパティは、サウンド名を取得または設定するために割り当てる必要があります。 読み書き String。

**戻り値:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```


遷移のサウンドの人間が読める名前を指定します。 Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) プロパティは、サウンド名を取得または設定するために割り当てる必要があります。 読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```


スライド遷移効果の持続時間をミリ秒単位で取得または設定します。 読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。 設定されていない場合、duration は \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) プロパティと遷移タイプに基づいて自動的に決定されます。

**戻り値:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```


スライド遷移効果の持続時間をミリ秒単位で取得または設定します。 読み書き int。

--------------------

PresentationML スキーマの p:transition 要素の p14:dur 属性に対応します。 設定されていない場合、duration は \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) プロパティと遷移タイプに基づいて自動的に決定されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


2 つの SlideShowTransition インスタンスが等しいかどうかを判定します。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在の SlideShowTransition と比較する SlideShowTransition。 |

**戻り値:**
boolean -  **true**  if the specified SlideShowTransition is equal to the current SlideShowTransition; otherwise,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型に対するハッシュ関数として機能し、ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できます。

**戻り値:**
int - 23454

--------------------

コンパイラを満足させるためにオーバーライドされています。 オブジェクトは可変であるため常に定数を返します。