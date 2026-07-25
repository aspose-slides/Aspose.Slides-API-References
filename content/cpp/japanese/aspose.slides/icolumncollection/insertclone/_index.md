---
title: InsertClone()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたテンプレート列のコピーを作成し、テーブルの指定された位置に挿入します。
type: docs
weight: 27
url: /ja/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) メソッド

指定されたテンプレート列のコピーを作成し、テーブルの指定された位置に挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新しい列のインデックス。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) はテンプレートとして使用されます。 |
| withAttachedColumns | **bool** | テンプレート列に添付されたすべての列もコピーする場合は True。 |

### 戻り値

挿入された列。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IColumn](../../icolumn/)
* クラス [IColumnCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)