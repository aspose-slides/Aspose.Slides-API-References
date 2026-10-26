---
title: TrendlineCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: Trendline のコレクションを表します
type: docs
url: /ja/com.aspose.slides/trendlinecollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline のコレクションを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(int trendlineType)](#add-int-) | 新しい Trendline をコレクションの末尾に追加し、返します。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 指定された値を削除します。 |
| [iterator()](#iterator--) | コレクションを列挙する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |

### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [Trendline](../../com.aspose.slides/trendline)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ITrendline](../../com.aspose.slides/itrendline)

### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

新しい Trendline をコレクションの末尾に追加し、返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| trendlineType | int |  |

**戻り値:**
[ITrendline](../../com.aspose.slides/itrendline)

### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

指定された値を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

コレクションを列挙する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.

### getCount() {#getCount--}
```
public final int getCount()
```

コレクションに実際に含まれる要素数を取得します。 読み取り専用 int。

**戻り値:**
int