---
title: Blur
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: Blur 効果を表します。シェイプ全体（塗りつぶしを含む）に適用されます。
type: docs
url: /ja/com.aspose.slides/blur/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Blur 効果を表します。シェイプ全体（塗りつぶしを含む）に適用され、アルファを含むすべてのカラーチャンネルが影響を受けます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | ぼかし半径を取得または設定します。 |
| [setRadius(double value)](#setRadius-double-) | ぼかし半径を取得または設定します。 |
| [getGrow()](#getGrow--) | ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを判断します。 |
| [setGrow(boolean value)](#setGrow-boolean-) | ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを判断します。 |
| [getEffective()](#getEffective--) | 継承が適用された実効的な Blur 効果データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [Blur](../../com.aspose.slides/blur) が現在の [Blur](../../com.aspose.slides/blur) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

ぼかし半径を取得または設定します。読み書き可能な double。

**戻り値:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

ぼかし半径を取得または設定します。読み書き可能な double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを判断します。true は境界が拡張されることを示し、false は拡張されないことを示します。読み書き可能な boolean。

**戻り値:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを判断します。true は境界が拡張されることを示し、false は拡張されないことを示します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

継承が適用された実効的な Blur 効果データを取得します。

**戻り値:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) のインスタンス。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [Blur](../../com.aspose.slides/blur) が現在の [Blur](../../com.aspose.slides/blur) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象となる [Blur](../../com.aspose.slides/blur)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。