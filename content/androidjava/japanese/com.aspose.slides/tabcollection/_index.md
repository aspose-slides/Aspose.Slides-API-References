---
title: TabCollection
second_title: Java API リファレンスによる Aspose.Slides for Android
description: タブのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/tabcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

タブのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(double position, int align)](#add-double-int-) | コレクションに Tab を追加します。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | コレクションに Tab を追加します。 |
| [clear()](#clear--) | コレクションのすべての要素を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 2 つの TabsEx インスタンスが等しいかどうかを判断します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [Tab](../../com.aspose.slides/tab).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

コレクションに Tab を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**戻り値:**
[ITab](../../com.aspose.slides/itab) - 追加されたタブ。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

コレクションに Tab を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | コレクションの末尾に追加される Tab オブジェクト。 |

**戻り値:**
int - タブが追加されたインデックス。
### clear() {#clear--}
```
public final void clear()
```

コレクションのすべての要素を削除します。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

2 つの TabsEx インスタンスが等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在の TabsEx と比較する TabsEx。 |

**戻り値:**
boolean - **true** if the specified TabsEx is equal to the current TabsEx; otherwise, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | ターゲット配列。 |
| index | int | ターゲット配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object