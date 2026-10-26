---
title: Duotone
second_title: Aspose.Slides for Java API リファレンス
description: Duotone エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/duotone/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Duotoneエフェクトを表します。各ピクセルについて、Color1とColor2を線形補間で組み合わせ、新しいピクセルのカラーを決定します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor1()](#getColor1--) | Returns target color format for dark pixels. |
| [getColor2()](#getColor2--) | Returns target color format for light pixels. |
| [getEffective()](#getEffective--) | Gets effective Duotone effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Duotone](../../com.aspose.slides/duotone) is equal to the current [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

暗いピクセル用のターゲットカラー形式を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

明るいピクセル用のターゲットカラー形式を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

継承が適用された有効なDuotoneエフェクトデータを取得します。

**戻り値:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) のインスタンス。

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された[Duotone](../../com.aspose.slides/duotone)が現在の[Duotone](../../com.aspose.slides/duotone)と等しいかどうかを判定します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象となる[Duotone](../../com.aspose.slides/duotone)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。