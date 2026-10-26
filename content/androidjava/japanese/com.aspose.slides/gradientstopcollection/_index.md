---
title: GradientStopCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: グラデーション ストップのコレクションを表します。
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

グラデーション ストップのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | コレクション内のグラデーション ストップの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでグラデーション ストップを返します。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのグラデーション ストップを削除します。 |
| [clear()](#clear--) | コレクションからすべてのグラデーション ストップを削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッド セーフ）。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### size() {#size--}
```
public final int size()
```

コレクション内のグラデーション ストップの数を返します。読み取り専用 int 。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

インデックスでグラデーション ストップを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| color | java.lang.Integer | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| presetColor | int | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| schemeColor | int | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| color | java.lang.Integer | 新しいグラデーション ストップの色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| presetColor | int | 新しいグラデーション ストップの色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

新しいグラデーション ストップを作成し、指定されたインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| schemeColor | int | 新しいグラデーション ストップの色。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのグラデーション ストップを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきグラデーション ストップのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのグラデーション ストップを削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - 全体のコレクション用 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目的配列。 |
| index | int | 目的配列での開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッド セーフ）。読み取り専用 boolean 。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object