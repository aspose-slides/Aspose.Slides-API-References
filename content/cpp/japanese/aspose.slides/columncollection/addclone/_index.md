---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテンプレート行のコピーを作成し、テーブルの下部に挿入します。
type: docs
weight: 53
url: /ja/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) メソッド


指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) はテンプレートとして使用されます。 |
| withAttachedColumns | **bool** | テンプレート行に添付されているすべての列もコピーする場合は true。 |

### 戻り値

追加された列。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)