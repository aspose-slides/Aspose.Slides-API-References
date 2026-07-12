---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 追加のカラースキームのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/extracolorschemecollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

追加のカラースキームのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスで色スキームを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | ArrayList へのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | コレクションへのアクセスを同期化するために使用できるオブジェクトを返します。 |
### size() {#size--}
```
public final int size()
```

コレクション内の要素数 (int) を返します。読み取り専用 int。

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

インデックスで色スキームを返します。読み取り専用 [ExtraColorScheme](../../com.aspose.slides/extracolorscheme)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**Returns:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

コレクションを反復する列挙子を返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

コレクション全体の java イテレータを返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 配列内の開始インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ArrayList へのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean。

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

コレクションへのアクセスを同期化するために使用できるオブジェクトを返します。読み取り専用 Object。

同期ルートを返します。読み取り専用 Object。

**Returns:**
java.lang.Object