---
title: MotionEffect
second_title: Aspose.Slides for Android の Java API リファレンス
description: エフェクトのモーション効果の動作を表します。
type: docs
url: /ja/com.aspose.slides/motioneffect/
---
**継承:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

エフェクトのモーション効果の動作を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrom()](#getFrom--) | アニメーションの開始位置となる x/y 座標を指定します（パーセンテージ単位）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | アニメーションの開始位置となる x/y 座標を指定します（パーセンテージ単位）。 |
| [getTo()](#getTo--) | アニメーションのモーション効果のターゲット位置を指定します（パーセンテージ単位）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | アニメーションのモーション効果のターゲット位置を指定します（パーセンテージ単位）。 |
| [getBy()](#getBy--) | アニメーションの相対オフセット値を記述します（パーセンテージ単位）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | アニメーションの相対オフセット値を記述します（パーセンテージ単位）。 |
| [getRotationCenter()](#getRotationCenter--) | モーションパスを X 角度で回転させる際に使用される回転の中心を記述します。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | モーションパスを X 角度で回転させる際に使用される回転の中心を記述します。 |
| [getOrigin()](#getOrigin--) | モーションパスの原点がスライドのレイアウトや親など、何に相対しているかを指定します。 |
| [setOrigin(int value)](#setOrigin-int-) | モーションパスの原点がスライドのレイアウトや親など、何に相対しているかを指定します。 |
| [getPath()](#getPath--) | アニメーションのモーションのための座標に続くパスプリミティブを指定します。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | アニメーションのモーションのための座標に続くパスプリミティブを指定します。 |
| [getPathEditMode()](#getPathEditMode--) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [getAngle()](#getAngle--) | モーションパスの相対角度を記述します。 |
| [setAngle(float value)](#setAngle-float-) | モーションパスの相対角度を記述します。 |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

アニメーションの開始位置となる x/y 座標を指定します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

アニメーションの開始位置となる x/y 座標を指定します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

アニメーションのモーション効果のターゲット位置を指定します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

アニメーションのモーション効果のターゲット位置を指定します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

アニメーションの相対オフセット値を記述します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

アニメーションの相対オフセット値を記述します（パーセンテージ単位）。 読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

モーションパスを X 角度で回転させる際に使用される回転の中心を記述します。 読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

モーションパスを X 角度で回転させる際に使用される回転の中心を記述します。 読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

モーションパスの原点がスライドのレイアウトや親など、何に相対しているかを指定します。 読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**戻り値:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

モーションパスの原点がスライドのレイアウトや親など、何に相対しているかを指定します。 読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

アニメーションのモーションのための座標に続くパスプリミティブを指定します。 読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**戻り値:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

アニメーションのモーションのための座標に続くパスプリミティブを指定します。 読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

シェイプが移動したときにモーションパスがどのように動くかを指定します。 読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**戻り値:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

シェイプが移動したときにモーションパスがどのように動くかを指定します。 読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

モーションパスの相対角度を記述します。 読み取り/書き込み float.

**戻り値:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

モーションパスの相対角度を記述します。 読み取り/書き込み float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |