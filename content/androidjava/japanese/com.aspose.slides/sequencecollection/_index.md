---
title: SequenceCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: インタラクティブ シーケンスのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/sequencecollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

インタラクティブ シーケンスのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクション内の要素数を返します 読み取り専用 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新しいインタラクティブ シーケンスを追加します。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | コレクションから指定されたシーケンスを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのシーケンスを削除します。 |
| [clear()](#clear--) | コレクションからすべてのシーケンスを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのシーケンスを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内の要素数を返します 読み取り専用 int。

**戻り値:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


新しいインタラクティブ シーケンスを追加します。読み書き可能 [Sequence](../../com.aspose.slides/sequence)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


コレクションから指定されたシーケンスを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 削除するシーケンス。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


指定されたインデックスのシーケンスを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきシーケンスのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```


コレクションからすべてのシーケンスを削除します。

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


指定されたインデックスのシーケンスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) オブジェクト。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - コレクション全体の java.util.Iterator。