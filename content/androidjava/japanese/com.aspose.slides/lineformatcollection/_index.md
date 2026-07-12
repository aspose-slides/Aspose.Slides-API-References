---
title: LineFormatCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 線スタイルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/lineformatcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

線スタイルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [size()](#size--) | コレクションに実際に含まれる要素の数を取得します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッド安全か）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期用のルートオブジェクトを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - コレクションを反復するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素の数を取得します。 読み取り専用 int。

**戻り値:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッド安全か）を示す値を返します。 読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期用のルートオブジェクトを返します。 読み取り専用 Object。

**戻り値:**
java.lang.Object