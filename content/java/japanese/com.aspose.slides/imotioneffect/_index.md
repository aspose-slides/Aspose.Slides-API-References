---
title: IMotionEffect
second_title: Aspose.Slides for Java API リファレンス
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
| [getFrom()](#getFrom--) | アニメーションの開始位置となる x/y 座標をパーセントで指定します。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | アニメーションの開始位置となる x/y 座標をパーセントで指定します。 |
| [getTo()](#getTo--) | アニメーションモーションエフェクトの対象位置をパーセントで指定します。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | アニメーションモーションエフェクトの対象位置をパーセントで指定します。 |
| [getBy()](#getBy--) | アニメーションの相対オフセット値をパーセントで記述します。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | アニメーションの相対オフセット値をパーセントで記述します。 |
| [getRotationCenter()](#getRotationCenter--) | X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 |
| [getOrigin()](#getOrigin--) | スライドのレイアウトや親など、モーションパスの起点が相対的に何であるかを指定します。 |
| [setOrigin(int value)](#setOrigin-int-) | スライドのレイアウトや親など、モーションパスの起点が相対的に何であるかを指定します。 |
| [getPath()](#getPath--) | アニメーションモーションのパスプリミティブと座標を指定します。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | アニメーションモーションのパスプリミティブと座標を指定します。 |
| [getPathEditMode()](#getPathEditMode--) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | シェイプが移動したときにモーションパスがどのように動くかを指定します。 |
| [getAngle()](#getAngle--) | モーションパスの相対角度を記述します。 |
| [setAngle(float value)](#setAngle-float-) | モーションパスの相対角度を記述します。 |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

アニメーションの開始位置となる x/y 座標をパーセントで指定します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

アニメーションの開始位置となる x/y 座標をパーセントで指定します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

アニメーションモーションエフェクトの対象位置をパーセントで指定します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

アニメーションモーションエフェクトの対象位置をパーセントで指定します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

アニメーションの相対オフセット値をパーセントで記述します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

アニメーションの相対オフセット値をパーセントで記述します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

X 角度でモーションパスを回転させる際に使用される回転中心を記述します。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

スライドのレイアウトや親など、モーションパスの起点が相対的に何であるかを指定します。 読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**戻り値:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

スライドのレイアウトや親など、モーションパスの起点が相対的に何であるかを指定します。 読み取り/書き込み [MotionOriginType](../../com.aspose.slides/motionorigintype).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

アニメーションモーションのパスプリミティブと座標を指定します。 読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**戻り値:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

アニメーションモーションのパスプリミティブと座標を指定します。 読み取り/書き込み [IMotionPath](../../com.aspose.slides/imotionpath).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

シェイプが移動したときにモーションパスがどのように動くかを指定します。 読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**戻り値:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

シェイプが移動したときにモーションパスがどのように動くかを指定します。 読み取り/書き込み [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

モーションパスの相対角度を記述します。 読み取り/書き込み float.

**戻り値:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

モーションパスの相対角度を記述します。 読み取り/書き込み float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |