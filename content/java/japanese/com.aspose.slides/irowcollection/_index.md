---
title: IRowCollection
second_title: Aspose.Slides for Java API リファレンス
description: テーブル行コレクションを表します。
type: docs
url: /ja/com.aspose.slides/irowcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

テーブル行コレクションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの指定された位置に挿入します。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | テーブルの指定された位置から行を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

指定されたインデックスの要素を取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に添付されているすべての行もコピーする場合は true に設定します。 |

**Returns:**
com.aspose.slides.IRow[] - 追加された行。
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

指定されたテンプレート行のコピーを作成し、テーブルの指定された位置に挿入します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 新しい行のインデックス。 |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に添付されているすべての行もコピーする場合は true に設定します。 |

**Returns:**
com.aspose.slides.IRow[] - 挿入された行。
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

テーブルの指定された位置から行を削除します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | 削除する行のインデックス。 |
| withAttachedRows | boolean | テンプレート行に添付されているすべての行も削除する場合は true に設定します。 |