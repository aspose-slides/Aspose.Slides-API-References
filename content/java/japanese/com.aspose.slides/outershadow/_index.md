---
title: OuterShadow
second_title: Aspose.Slides for Java API リファレンス
description: 外部影効果を表します。
type: docs
url: /ja/com.aspose.slides/outershadow/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

外部影効果を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径（ポイント単位）。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径（ポイント単位）。 |
| [getDirection()](#getDirection--) | 影の方向（度単位）。 |
| [setDirection(float value)](#setDirection-float-) | 影の方向（度単位）。 |
| [getDistance()](#getDistance--) | オブジェクトから影までの距離（ポイント単位）。 |
| [setDistance(double value)](#setDistance-double-) | オブジェクトから影までの距離（ポイント単位）。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平歪み角度（度単位）。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平歪み角度（度単位）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直歪み角度（度単位）。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直歪み角度（度単位）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 影がシェイプとともに回転するかどうかを示します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 影がシェイプとともに回転するかどうかを示します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 元のサイズに対する水平スケーリング係数（パーセンテージ）。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 元のサイズに対する水平スケーリング係数（パーセンテージ）。 |
| [getScaleVertical()](#getScaleVertical--) | 元のサイズに対する垂直スケーリング係数（パーセンテージ）。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 元のサイズに対する垂直スケーリング係数（パーセンテージ）。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な外部影効果データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [OuterShadow](../../com.aspose.slides/outershadow) が現在の [OuterShadow](../../com.aspose.slides/outershadow) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

ぼかし半径（ポイント単位）。 デフォルト値 - 0 pt。 読み書き double。

**戻り値:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

ぼかし半径（ポイント単位）。 デフォルト値 - 0 pt。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

影の方向（度単位）。 デフォルト値 - 0 �（左から右）。 読み書き float。

**戻り値:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

影の方向（度単位）。 デフォルト値 - 0 �（左から右）。 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

オブジェクトから影までの距離（ポイント単位）。 デフォルト値 - 0 pt。 読み書き double。

**戻り値:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

オブジェクトから影までの距離（ポイント単位）。 デフォルト値 - 0 pt。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

影の色。 デフォルト値 - 自動的な黒（テーマ依存）。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形の配置。 デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。 読み書き [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形の配置。 デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。 読み書き [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

水平歪み角度（度単位）。 デフォルト値 - 0 �。 読み書き double。

**戻り値:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

水平歪み角度（度単位）。 デフォルト値 - 0 �。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

垂直歪み角度（度単位）。 デフォルト値 - 0 �。 読み書き double。

**戻り値:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

垂直歪み角度（度単位）。 デフォルト値 - 0 �。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

影がシェイプとともに回転するかどうかを示します。 デフォルト値 - true。 読み書き boolean。

**戻り値:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

影がシェイプとともに回転するかどうかを示します。 デフォルト値 - true。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

元のサイズに対する水平スケーリング係数（パーセンテージ）。 負のスケーリングは反転を引き起こします。 デフォルト値 - 100%。 読み書き double。

**戻り値:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

元のサイズに対する水平スケーリング係数（パーセンテージ）。 負のスケーリングは反転を引き起こします。 デフォルト値 - 100%。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

元のサイズに対する垂直スケーリング係数（パーセンテージ）。 負のスケーリングは反転を引き起こします。 デフォルト値 - 100%。 読み書き double。

**戻り値:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

元のサイズに対する垂直スケーリング係数（パーセンテージ）。 負のスケーリングは反転を引き起こします。 デフォルト値 - 100%。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

継承が適用された有効な外部影効果データを取得します。

**戻り値:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を返します。 読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [OuterShadow](../../com.aspose.slides/outershadow) が現在の [OuterShadow](../../com.aspose.slides/outershadow) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [OuterShadow](../../com.aspose.slides/outershadow)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。