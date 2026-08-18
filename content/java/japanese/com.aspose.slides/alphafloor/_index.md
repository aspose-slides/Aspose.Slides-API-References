---
title: AlphaFloor
second_title: Aspose.Slides for Java API リファレンス
description: Alpha Floor エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphafloor/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Alpha Floor エフェクトを表します。Alpha（opacity）の値が 100% 未満の場合は 0 に変更されます。言い換えれば、部分的に透明なものはすべて完全に透明になります。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
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