---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテンプレート行のコピーを作成し、テーブルの下部に挿入します。
type: docs
weight: 53
url: /ja/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) メソッド

Creates a copy of the specified template row and inserts it at the bottom of a table.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) テンプレートとして使用されます。 |
| withAttachedRows | **bool** | テンプレート行に添付されたすべての行もコピーするには true を指定します。 |

### 戻り値

追加された行。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IRow](../../irow/)
* クラス [RowCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)