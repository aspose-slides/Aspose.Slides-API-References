---
title: Duotone
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Duotone エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/duotone/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Duotone エフェクトを表します。各ピクセルについて、Color1 と Color2 を線形補間で組み合わせて、そのピクセルの新しい色を決定します。

## Methods

| Method | Description |
| --- | --- |
| [getColor1()](#getColor1--) | 暗いピクセル用のターゲットカラー形式を返します。 |
| [getColor2()](#getColor2--) | 明るいピクセル用のターゲットカラー形式を返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Duotone エフェクトデータを取得します。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [Duotone](../../com.aspose.slides/duotone) が現在の [Duotone](../../com.aspose.slides/duotone) と等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

暗いピクセル用のターゲットカラー形式を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

明るいピクセル用のターゲットカラー形式を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

継承が適用された有効な Duotone エフェクトデータを取得します。

**戻り値:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [Duotone](../../com.aspose.slides/duotone) が現在の [Duotone](../../com.aspose.slides/duotone) と等しいかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [Duotone](../../com.aspose.slides/duotone)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。