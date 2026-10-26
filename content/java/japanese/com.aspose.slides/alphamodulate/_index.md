---
title: AlphaModulate
second_title: Aspose.Slides for Java API リファレンス
description: Alpha Modulate エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphamodulate/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Alpha Modulate エフェクトを表します。エフェクトのアルファ (不透明度) 値は固定のパーセンテージで乗算されます。エフェクト コンテナは、アルファ値を変調するエフェクトを指定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Modulate エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaModulate](../../com.aspose.slides/alphamodulate) が現在の [AlphaModulate](../../com.aspose.slides/alphamodulate) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


継承が適用された有効な Alpha Modulate エフェクト データを取得します。

**戻り値:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) のインスタンス。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [AlphaModulate](../../com.aspose.slides/alphamodulate) が現在の [AlphaModulate](../../com.aspose.slides/alphamodulate) と等しいかどうかを判断します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaModulate](../../com.aspose.slides/alphamodulate) を比較対象として使用します。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。