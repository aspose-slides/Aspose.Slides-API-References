---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: SmartArt ノードのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/smartartnodecollection/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

SmartArt ノードのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでノードを返します |
| [size()](#size--) | コレクション内のノード数を返します 読み取り専用 int 読み取り専用 int。 |
| [addNode()](#addNode--) | 新しい SmartArt ノードまたはサブノードを追加します。 |
| [removeNode(int index)](#removeNode-int-) | インデックスでノードまたはサブノードを削除します |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | ノードまたはサブノードを削除します |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | ノードコレクションの選択された位置に新しいノードを追加します |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションから指定された配列へすべての要素をコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


インデックスでノードを返します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のゼロベースインデックス |

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt ノード
### size() {#size--}
```
public final int size()
```


コレクション内のノード数を返します 読み取り専用 int 読み取り専用 int。

**戻り値:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


新しい SmartArt ノードまたはサブノードを追加します。

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 追加されたノード
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


インデックスでノードまたはサブノードを削除します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ノードのゼロベースインデックス |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


ノードまたはサブノードを削除します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 削除するノード |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


ノードコレクションの選択された位置に新しいノードを追加します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | int | ノードのゼロベース位置 |

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 追加されたノード
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションから指定された配列へすべての要素をコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象の配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します 読み取り専用 boolean 。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期化ルートを返します。 読み取り専用 Object。

**戻り値:**
java.lang.Object