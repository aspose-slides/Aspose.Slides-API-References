---
title: RowCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: テーブル行コレクションを表します。
type: docs
url: /ja/com.aspose.slides/rowcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

テーブル行コレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれている行数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの行を返します。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの指定位置に挿入します。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | テーブルの指定位置から行を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化のルートを返します。 |
### size() {#size--}
```
public final int size()
```


コレクションに実際に含まれている行数を取得します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


指定されたインデックスの行を返します。読み取り専用 [Row](../../com.aspose.slides/row)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に添付されたすべての行もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IRow[] - 追加された行。
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


指定されたテンプレート行のコピーを作成し、テーブルの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい行のインデックス。 |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に添付されたすべての行もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IRow[] - 挿入された行。
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


テーブルの指定位置から行を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstRowIndex | int | 削除する行のインデックス。 |
| withAttachedRows | boolean | 添付されたすべての行も削除する場合は true。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - コレクション全体の java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
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


同期化のルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object