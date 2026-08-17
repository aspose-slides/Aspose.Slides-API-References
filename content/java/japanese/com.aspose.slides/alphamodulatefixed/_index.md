---
title: AlphaModulateFixed
second_title: Aspose.Slides の Java API リファレンス
description: Alpha Modulate Fixed エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphamodulatefixed/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Alpha Modulate Fixed エフェクトを表します。エフェクトのアルファ (不透明度) 値は固定パーセンテージで乗算されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAmount()](#getAmount--) | エフェクトの量をパーセントで返します。 |
| [setAmount(float value)](#setAmount-float-) | エフェクトの量をパーセントで返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Modulate Fixed エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) が現在の [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getAmount() {#getAmount--}
```
public final float getAmount()
```


エフェクトの量をパーセントで返します。読み書き float.

**戻り値:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```


エフェクトの量をパーセントで返します。読み書き float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```


継承が適用された有効な Alpha Modulate Fixed エフェクト データを取得します。

**戻り値:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - A [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) が現在の [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでなければ false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。