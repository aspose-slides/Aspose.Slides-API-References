---
title: Reflection
second_title: Aspose.Slides for Android の Java API リファレンス
description: Reflection エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/reflection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reflection エフェクトを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 開始アルファ値（パーセンテージ）の開始位置（アルファグラデーションランプに沿って）を指定します。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 開始アルファ値（パーセンテージ）の開始位置（アルファグラデーションランプに沿って）を指定します。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 終了アルファ値（パーセンテージ）の終了位置（アルファグラデーションランプに沿って）を指定します。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 終了アルファ値（パーセンテージ）の終了位置（アルファグラデーションランプに沿って）を指定します。 |
| [getFadeDirection()](#getFadeDirection--) | Reflection のオフセット方向を指定します。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Reflection のオフセット方向を指定します。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 開始時の Reflection の不透明度です。 |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 開始時の Reflection の不透明度です。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 終了時の Reflection の不透明度です。 |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 終了時の Reflection の不透明度です。 |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径です。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径です。 |
| [getDirection()](#getDirection--) | Reflection の方向です。 |
| [setDirection(float value)](#setDirection-float-) | Reflection の方向です。 |
| [getDistance()](#getDistance--) | Reflection の距離です。 |
| [setDistance(double value)](#setDistance-double-) | Reflection の距離です。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置です。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置です。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平せん断角度を指定します。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平せん断角度を指定します。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直せん断角度を指定します。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直せん断角度を指定します。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | シェイプが回転した場合に、Reflection がシェイプとともに回転すべきかどうかを指定します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | シェイプが回転した場合に、Reflection がシェイプとともに回転すべきかどうかを指定します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） |
| [getScaleVertical()](#getScaleVertical--) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） |
| [getEffective()](#getEffective--) | 継承が適用された有効な Reflection エフェクトデータを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [Reflection](../../com.aspose.slides/reflection) が現在の [Reflection](../../com.aspose.slides/reflection) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```


開始アルファ値（パーセンテージ）の開始位置（アルファグラデーションランプに沿って）を指定します。 読み取り/書き込み可能な float。

**戻り値:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```


開始アルファ値（パーセンテージ）の開始位置（アルファグラデーションランプに沿って）を指定します。 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```


終了アルファ値（パーセンテージ）の終了位置（アルファグラデーションランプに沿って）を指定します。 読み取り/書き込み可能な float。

**戻り値:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```


終了アルファ値（パーセンテージ）の終了位置（アルファグラデーションランプに沿って）を指定します。 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```


Reflection のオフセット方向を指定します。（角度） 読み取り/書き込み可能な float。

**戻り値:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```


Reflection のオフセット方向を指定します。（角度） 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```


開始時の Reflection の不透明度です。（パーセンテージ） 読み取り/書き込み可能な float。

**戻り値:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```


開始時の Reflection の不透明度です。（パーセンテージ） 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```


終了時の Reflection の不透明度です。（パーセンテージ） 読み取り/書き込み可能な float。

**戻り値:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```


終了時の Reflection の不透明度です。（パーセンテージ） 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


ぼかし半径です。 読み取り/書き込み可能な double。

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


ぼかし半径です。 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```


Reflection の方向です。 読み取り/書き込み可能な float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Reflection の方向です。 読み取り/書き込み可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Reflection の距離です。 読み取り/書き込み可能な double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Reflection の距離です。 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```


矩形の配置です。 読み取り/書き込み可能な [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```


矩形の配置です。 読み取り/書き込み可能な [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```


水平せん断角度を指定します。 読み取り/書き込み可能な double。

**戻り値:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```


水平せん断角度を指定します。 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```


垂直せん断角度を指定します。 読み取り/書き込み可能な double。

**戻り値:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```


垂直せん断角度を指定します。 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```


シェイプが回転した場合に、Reflection がシェイプとともに回転すべきかどうかを指定します。 読み取り/書き込み可能な boolean。

**戻り値:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```


シェイプが回転した場合に、Reflection がシェイプとともに回転すべきかどうかを指定します。 読み取り/書き込み可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```


水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） 読み取り/書き込み可能な double。

**戻り値:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```


水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```


垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） 読み取り/書き込み可能な double。

**戻り値:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```


垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセンテージ） 読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```


継承が適用された有効な Reflection エフェクトデータを取得します。

**戻り値:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


バージョンです。読み取り専用 long。

**戻り値:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [Reflection](../../com.aspose.slides/reflection) が現在の [Reflection](../../com.aspose.slides/reflection) と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [Reflection](../../com.aspose.slides/reflection)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、それ以外は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。