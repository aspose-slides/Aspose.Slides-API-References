---
title: PointCollection
second_title: Aspose.Slides for Java APIリファレンス
description: アニメーションポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/pointcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

アニメーションポイントのコレクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of points in the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a point at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |

### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内のポイントの数を返します。読み取り専用 int.

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

指定されたインデックスのポイントを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Index of element. |

**戻り値:**
[IPoint](../../com.aspose.slides/ipoint) - The [IPoint](../../com.aspose.slides/ipoint) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - コレクション全体の java.util.Iterator。