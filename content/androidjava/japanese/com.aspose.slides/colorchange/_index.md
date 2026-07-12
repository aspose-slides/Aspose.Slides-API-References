---
title: ColorChange
second_title: Aspose.Slides for Android の Java API リファレンス
description: カラー変更エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/colorchange/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect  
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Color Change エフェクトを表します。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 置き換えられるカラー。 |
| [getToColor()](#getToColor--) | 置き換えるカラー。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Color Change エフェクト データを取得します。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [ColorChange](../../com.aspose.slides/colorchange) が現在の [ColorChange](../../com.aspose.slides/colorchange) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

置き換えられるカラー。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

置き換えるカラー。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

継承が適用された有効な Color Change エフェクト データを取得します。

**戻り値:**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata)。

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

指定された [ColorChange](../../com.aspose.slides/colorchange) が現在の [ColorChange](../../com.aspose.slides/colorchange) と等しいかどうかを判断します。

**パラメータ:**  

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [ColorChange](../../com.aspose.slides/colorchange)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。