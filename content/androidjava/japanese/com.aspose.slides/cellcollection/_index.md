---
title: CellCollection
second_title: Aspose.Slides for Android via Java API リファレンス
description: セルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/cellcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

セルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | コレクション内のセルの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定された位置のセルを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getSlide()](#getSlide--) | CellCollection の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | CellCollection の親プレゼンテーションを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


コレクション内のセルの数を返します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


指定された位置のセルを返します。読み取り専用 [Cell](../../com.aspose.slides/cell)。

--------------------

セルが結合されている場合、1つの Cell オブジェクトが複数のインデックスに対して返されることがあります。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 全体のコレクション用 java.util.Iterator。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


CellCollection の親スライドを返します。読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


CellCollection の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | ターゲット配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object