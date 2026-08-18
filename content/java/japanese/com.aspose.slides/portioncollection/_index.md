---
title: PortionCollection
second_title: Aspose.Slides for Java API リファレンス
description: Portion のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/portioncollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

コレクションの一部を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 指定されたインデックスの要素を取得します。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Portion をコレクションの末尾に追加します。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | リスト内の特定のアイテムのインデックスを決定します。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 指定されたインデックスに Portion をコレクションに挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列へコピーします。コピーは特定の配列インデックスから開始します。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### getCount() {#getCount--}
```
public final int getCount()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。読み取り専用 boolean。

**戻り値:**
boolean - true は [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合、false はそれ以外の場合です。
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Portion をコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | コレクションの末尾に追加される Portion。 |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

リスト内の特定のアイテムのインデックスを決定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | リストで検索するオブジェクト。 |

**戻り値:**
int - アイテムがリストに存在する場合はそのインデックス、存在しない場合は -1。
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

指定されたインデックスに Portion をコレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | Portion を挿入すべきゼロベースインデックス。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 挿入する Portion。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) で検索するオブジェクト。 |

**戻り値:**
boolean - true は [IGenericCollection](../../com.aspose.slides/igenericcollection) にアイテムが存在する場合、false はそれ以外の場合です。
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列へコピーします。コピーは特定の配列インデックスから開始します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列。配列はゼロベースインデックスである必要があります。 |
| arrayIndex | int | コピー開始位置となる配列のゼロベースインデックス。 |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**戻り値:**
boolean - true は [IGenericCollection](../../com.aspose.slides/igenericcollection) からアイテムが正常に削除された場合、false はそれ以外の場合です。このメソッドはアイテムが元の [IGenericCollection](../../com.aspose.slides/igenericcollection) に存在しない場合も false を返します。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - コレクション全体の java.util.Iterator。