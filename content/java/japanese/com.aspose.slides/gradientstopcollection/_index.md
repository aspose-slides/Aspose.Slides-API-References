---
title: GradientStopCollection
second_title: Aspose.Slides for Java API リファレンス
description: 勾配ストップのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/gradientstopcollection/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

勾配ストップのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | コレクション内の勾配ストップの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスで勾配ストップを返します。 |
| [add(float position, Color color)](#add-float-java.awt.Color-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | 新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの勾配ストップを削除します。 |
| [clear()](#clear--) | コレクションからすべての勾配ストップを削除します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションからすべての要素を指定された配列へコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. 読み取り専用 long。

**戻り値:**
long

### size() {#size--}
```
public final int size()
```

コレクション内の勾配ストップの数を返します。読み取り専用 int。

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

インデックスで勾配ストップを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| color | java.awt.Color | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| presetColor | int | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| schemeColor | int | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コレクション内で新しい勾配ストップが挿入されるインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| color | java.awt.Color | 新しい勾配ストップの色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コレクション内で新しい勾配ストップが挿入されるインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| presetColor | int | 新しい勾配ストップの色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

新しい勾配ストップを作成し、コレクションの指定されたインデックスに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コレクション内で新しい勾配ストップが挿入されるインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| schemeColor | int | 新しい勾配ストップの色。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの勾配ストップを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき勾配ストップのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての勾配ストップを削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - コレクションを反復するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - コレクション全体の java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションからすべての要素を指定された配列へコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object