---
title: IColumnCollection
second_title: Java API を介した Android 用 Aspose.Slides リファレンス
description: テーブル内の列のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icolumncollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

テーブル内の列のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの列を返します。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの下部に挿入します。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 指定されたテンプレート列のコピーを作成し、テーブルの指定された位置に挿入します。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | テーブルから指定された位置の列を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

指定されたインデックスの列を返します。読み取り専用 [IColumn](../../com.aspose.slides/icolumn)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

指定されたテンプレート行のコピーを作成し、テーブルの下部に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | テンプレートとして使用される列。 |
| withAttachedColumns | boolean | テンプレート行に添付されているすべての列もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IColumn[] - 追加された列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

指定されたテンプレート列のコピーを作成し、テーブルの指定された位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい列のインデックス。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | テンプレートとして使用される列。 |
| withAttachedColumns | boolean | テンプレート列に添付されているすべての列もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IColumn[] - 挿入された列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

テーブルから指定された位置の列を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstColumnIndex | int | 削除する列のインデックス。 |
| withAttachedRows | boolean | 添付されたすべての列も削除する場合は true。 |