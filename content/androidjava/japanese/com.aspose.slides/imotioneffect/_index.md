---
title: IMotionEffect
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: エフェクトのモーションエフェクトの動作を表します。
type: docs
url: /ja/com.aspose.slides/imotioneffect/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

エフェクトのモーションエフェクトの動作を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrom()](#getFrom--) | アニメーションの開始座標となる x/y 座標をパーセンテージで指定します。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | アニメーションの開始座標となる x/y 座標をパーセンテージで指定します。 |
| [getTo()](#getTo--) | アニメーションのモーションエフェクトの対象位置をパーセンテージで指定します。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | アニメーションのモーションエフェクトの対象位置をパーセンテージで指定します。 |
| [getBy()](#getBy--) | アニメーションの相対オフセット値をパーセンテージで記述します。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | アニメーションの相対オフセット値をパーセンテージで記述します。 |
| [getRotationCenter()](#getRotationCenter--) | X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 |
| [getOrigin()](#getOrigin--) | スライドのレイアウトや親など、モーションパスの起点が何に対して相対的かを指定します。 |
| [setOrigin(int value)](#setOrigin-int-) | スライドのレイアウトや親など、モーションパスの起点が何に対して相対的かを指定します。 |
| [getPath()](#getPath--) | アニメーションのモーションのために座標が続くパスプリミティブを指定します。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | アニメーションのモーションのために座標が続くパスプリミティブを指定します。 |
| [getPathEditMode()](#getPathEditMode--) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [getAngle()](#getAngle--) | モーションパスの相対角度を記述します。 |
| [setAngle(float value)](#setAngle-float-) | モーションパスの相対角度を記述します。 |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```


アニメーションの開始座標となる x/y 座標をパーセンテージで指定します。読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```


アニメーションの開始座標となる x/y 座標をパーセンテージで指定します。読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```


アニメーションのモーションエフェクトの対象位置をパーセンテージで指定します。読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```


アニメーションのモーションエフェクトの対象位置をパーセンテージで指定します。読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```


アニメーションの相対オフセット値をパーセンテージで記述します。読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```


アニメーションの相対オフセット値をパーセンテージで記述します。読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```


X 角度でモーションパスを回転させる際に使用される回転中心を記述します。読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```


X 角度でモーションパスを回転させる際に使用される回転中心を記述します。読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```


スライドのレイアウトや親など、モーションパスの起点が何に対して相対的かを指定します。読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**戻り値:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```


スライドのレイアウトや親など、モーションパスの起点が何に対して相対的かを指定します。読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```


アニメーションのモーションのために座標が続くパスプリミティブを指定します。読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**戻り値:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```


アニメーションのモーションのために座標が続くパスプリミティブを指定します。読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```


シェイプが移動したときにモーションパスがどのように動くかを指定します。読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**戻り値:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```


シェイプが移動したときにモーションパスがどのように動くかを指定します。読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```


モーションパスの相対角度を記述します。読み取り/書き込み float.

**戻り値:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```


モーションパスの相対角度を記述します。読み取り/書き込み float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |