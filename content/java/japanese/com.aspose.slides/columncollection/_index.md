---
title: ColumnCollection
second_title: Aspose.Slides for Java API リファレンス
description: テーブル内の列のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/columncollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

テーブル内の列のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の列数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの列を返します。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 指定されたテンプレート列のコピーを作成し、テーブルの指定位置に挿入します。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | テーブルから指定された位置にある列を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### size() {#size--}
```
public final int size()
```


コレクション内の列数を返します。 読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


指定されたインデックスの列を返します。 読み取り専用 [Column](../../com.aspose.slides/column)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | テンプレートとして使用される列。 |
| withAttachedColumns | boolean | テンプレート行に添付されたすべての列もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IColumn[] - 追加された列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


指定されたテンプレート列のコピーを作成し、テーブルの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい列のインデックス。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | テンプレートとして使用される列。 |
| withAttachedColumns | boolean | テンプレート列に添付されたすべての列もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IColumn[] - 挿入された列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


テーブルから指定された位置にある列を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstColumnIndex | int | 削除する列のインデックス。 |
| withAttachedRows | boolean | 添付されたすべての列も削除する場合は true。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - コレクション全体の java.util.Iterator。
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


コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。 読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。 読み取り専用 Object。

**戻り値:**
java.lang.Object