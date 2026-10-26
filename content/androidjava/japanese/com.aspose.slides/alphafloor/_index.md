---
title: AlphaFloor
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: Alpha Floor エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphafloor/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Alpha Floor エフェクトを表します。Alpha（不透明度）の 100% 未満の値は 0 に変更されます。言い換えれば、部分的に透明なものはすべて完全に透明になります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Floor エフェクトデータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaFloor](../../com.aspose.slides/alphafloor) が現在の [AlphaFloor](../../com.aspose.slides/alphafloor) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

継承が適用された有効な Alpha Floor エフェクトデータを取得します。

**戻り値:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) のインスタンス。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [AlphaFloor](../../com.aspose.slides/alphafloor) が現在の [AlphaFloor](../../com.aspose.slides/alphafloor) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [AlphaFloor](../../com.aspose.slides/alphafloor)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。