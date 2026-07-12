---
title: IRowCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: テーブル行コレクションを表します。
type: docs
url: /ja/com.aspose.slides/irowcollection/
---
**実装されているすべてのインターフェース:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

テーブル行コレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 指定されたテンプレート行のコピーを作成し、テーブルの指定位置に挿入します。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | テーブルの指定位置から行を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に付随するすべての行もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IRow[] - 追加された行。
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

指定されたテンプレート行のコピーを作成し、テーブルの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい行のインデックス。 |
| templ | [IRow](../../com.aspose.slides/irow) | テンプレートとして使用される行。 |
| withAttachedRows | boolean | テンプレート行に付随するすべての行もコピーする場合は true。 |

**戻り値:**
com.aspose.slides.IRow[] - 挿入された行。
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

テーブルの指定位置から行を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstRowIndex | int | 削除する行のインデックス。 |
| withAttachedRows | boolean | 付随するすべての行も削除する場合は true。 |