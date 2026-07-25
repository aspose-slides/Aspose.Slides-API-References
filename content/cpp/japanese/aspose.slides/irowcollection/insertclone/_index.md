---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテンプレート行のコピーを作成し、テーブル内の指定された位置に挿入します。
type: docs
weight: 27
url: /ja/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) メソッド


指定されたテンプレート行のコピーを作成し、テーブル内の指定された位置に挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しい行のインデックス。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) はテンプレートとして使用されます。 |
| withAttachedRows | **bool** | True はテンプレート行に添付されているすべての行もコピーします。 |

### 戻り値

挿入された行。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IRow](../../irow/)
* クラス [IRowCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)