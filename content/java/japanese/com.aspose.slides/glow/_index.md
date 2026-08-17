---
title: Glow
second_title: Aspose.Slides の Java API リファレンス
description: オブジェクトのエッジの外側に色がぼやけた輪郭を追加する Glow エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/glow/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

オブジェクトのエッジの外側に色がぼやけた輪郭を追加する Glow エフェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | 半径。 |
| [setRadius(double value)](#setRadius-double-) | 半径。 |
| [getColor()](#getColor--) | 色形式。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なGlowエフェクトデータを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された[Glow](../../com.aspose.slides/glow)が現在の[Glow](../../com.aspose.slides/glow)と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

半径。 読み書き可能 double 。

**戻り値:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

半径。 読み書き可能 double 。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

色形式。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

継承が適用された有効なGlowエフェクトデータを取得します。

**戻り値:**  
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)

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

parent IPresentationComponent を返します。 読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された[Glow](../../com.aspose.slides/glow)が現在の[Glow](../../com.aspose.slides/glow)と等しいかどうかを判断します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の[Glow](../../com.aspose.slides/glow)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**  
int - A hash code for the current object.