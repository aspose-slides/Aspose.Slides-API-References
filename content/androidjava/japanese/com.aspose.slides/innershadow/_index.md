---
title: InnerShadow
second_title: Aspose.Slides for Android の Java API リファレンス
description: 内部シャドウ効果を表します。
type: docs
url: /ja/com.aspose.slides/innershadow/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

内部シャドウ効果を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径。 |
| [getDirection()](#getDirection--) | 影の方向。 |
| [setDirection(float value)](#setDirection-float-) | 影の方向。 |
| [getDistance()](#getDistance--) | 影の距離。 |
| [setDistance(double value)](#setDistance-double-) | 影の距離。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な内部シャドウ効果データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [InnerShadow](../../com.aspose.slides/innershadow) が現在の [InnerShadow](../../com.aspose.slides/innershadow) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

ぼかし半径。読み書き double.

**戻り値:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

ぼかし半径。読み書き double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

影の方向。読み書き float.

**戻り値:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

影の方向。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

影の距離。読み書き double.

**戻り値:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

影の距離。読み書き double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

影の色。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

継承が適用された有効な内部シャドウ効果データを取得します。

**戻り値:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) のインスタンス。

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

バージョン。読み取り専用 long。

**戻り値:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent の親を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [InnerShadow](../../com.aspose.slides/innershadow) が現在の [InnerShadow](../../com.aspose.slides/innershadow) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [InnerShadow](../../com.aspose.slides/innershadow)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。