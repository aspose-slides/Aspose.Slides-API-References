---
title: AddClone()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。
type: docs
weight: 14
url: /ja/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) はテンプレートとして使用されます。 |
| withAttachedColumns | **bool** | True テンプレート行に添付されたすべての列もコピーします。 |

### 戻り値

追加された列。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IColumn](../../icolumn/)
* クラス [IColumnCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)