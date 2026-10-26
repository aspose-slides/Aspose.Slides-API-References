---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。
type: docs
weight: 14
url: /ja/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) メソッド

指定されたテンプレート行のコピーを作成し、テーブルの末尾に挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) はテンプレートとして使用されます。 |
| withAttachedRows | **bool** | true を指定するとテンプレート行に添付されたすべての行もコピーします。 |

### 戻り値

追加された行。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IRow](../../irow/)
* クラス [IRowCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)