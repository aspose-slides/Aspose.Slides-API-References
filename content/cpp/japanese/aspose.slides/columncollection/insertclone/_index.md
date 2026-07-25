---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテンプレート列のコピーを作成し、テーブルの指定位置に挿入します。
type: docs
weight: 66
url: /ja/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

指定されたテンプレート列のコピーを作成し、テーブルの指定位置に挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しい列のインデックス。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) テンプレートとして使用されます。 |
| withAttachedColumns | **bool** | True を指定すると、テンプレート列に付随するすべての列もコピーされます。 |

### 戻り値

挿入された列。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IColumn](../../icolumn/)
* クラス [ColumnCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)