---
title: LayoutSlideCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: レイアウトスライドのコレクションの基底クラスを表します。
type: docs
url: /ja/com.aspose.slides/layoutslidecollection/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

レイアウトスライドのコレクションの基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のレイアウトスライドの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでレイアウトスライドを返します。 |
| [getByType(byte type)](#getByType-byte-) | 指定されたタイプの最初のレイアウトスライドを返します。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | コレクションからレイアウトを削除します。 |
| [removeUnused()](#removeUnused--) | 未使用のレイアウトスライドを削除します（HasDependingSlides が false のレイアウトスライド）。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

コレクション内のレイアウトスライドの数を返します。読み取り専用 int。

**戻り値:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

インデックスでレイアウトスライドを返します。読み取り専用 [LayoutSlide](../../com.aspose.slides/layoutslide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

指定されたタイプの最初のレイアウトスライドを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | byte | 検索するレイアウトスライドのタイプ。 |

**戻り値:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide)（指定されたタイプ）またはレイアウトが見つからない場合は null。

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

コレクションからレイアウトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | コレクションから削除するレイアウトスライド。 |

--------------------

1) PptxEditException のスローを防ぐために、事前にレイアウトの HasDependingSlides プロパティをチェックしてください。 2) コードを簡素化するために [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) メソッドも使用できます。

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

未使用のレイアウトスライドを削除します（HasDependingSlides が false のレイアウトスライド）。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標配列。 |
| index | int | 目標配列内の開始インデックス。 |

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

同期化ルートを返します。読み取り専用 Object。

**戻り値:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**  
com.aspose.slides.IDOMObject