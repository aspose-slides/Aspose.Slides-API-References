---
title: SoftEdge
second_title: Android 向け Aspose.Slides の Java API リファレンス
description: ソフトエッジ効果を表します。
type: docs
url: /ja/com.aspose.slides/softedge/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

ソフトエッジ効果を表します。形状のエッジはぼやけますが、塗りつぶしは影響を受けません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | エッジに適用するぼかしの半径を指定します。 |
| [setRadius(double value)](#setRadius-double-) | エッジに適用するぼかしの半径を指定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Soft Edge 効果データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [SoftEdge](../../com.aspose.slides/softedge) が現在の [SoftEdge](../../com.aspose.slides/softedge) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

エッジに適用するぼかしの半径を指定します。読み書き可能 double。

**戻り値:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

エッジに適用するぼかしの半径を指定します。読み書き可能 double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

継承が適用された有効な Soft Edge 効果データを取得します。

**戻り値:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)。

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

親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [SoftEdge](../../com.aspose.slides/softedge) が現在の [SoftEdge](../../com.aspose.slides/softedge) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象となる [SoftEdge](../../com.aspose.slides/softedge)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。