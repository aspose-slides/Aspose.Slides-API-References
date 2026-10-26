---
title: IRevealTransition
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド遷移エフェクトを表示します。
type: docs
url: /ja/com.aspose.slides/irevealtransition/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IRevealTransition extends ITransitionValueBase
```

スライド遷移エフェクトを表示します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | 遷移の方向。 |
| [setDirection(int value)](#setDirection-int-) | 遷移の方向。 |
| [getThroughBlack()](#getThroughBlack--) | 遷移がブラックフェードするかどうかを指定します。 |
| [setThroughBlack(boolean value)](#setThroughBlack-boolean-) | 遷移がブラックフェードするかどうかを指定します。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


遷移の方向。読み取り/書き込み [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype)。

**戻り値:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


遷移の方向。読み取り/書き込み [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getThroughBlack() {#getThroughBlack--}
```
public abstract boolean getThroughBlack()
```


遷移がブラックフェードするかどうかを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setThroughBlack(boolean value) {#setThroughBlack-boolean-}
```
public abstract void setThroughBlack(boolean value)
```


遷移がブラックフェードするかどうかを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |