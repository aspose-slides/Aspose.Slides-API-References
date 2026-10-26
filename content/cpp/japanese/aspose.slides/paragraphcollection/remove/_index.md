---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: ICollection から特定のオブジェクトの最初の出現を削除します。
type: docs
weight: 131
url: /ja/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) メソッド

特定のオブジェクトの最初の出現を [ICollection](../../../system.collections.generic/icollection/) から削除します。

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [ICollection](../../../system.collections.generic/icollection/) から削除するオブジェクト。 |

### 戻り値

*item* が [ICollection](../../../system.collections.generic/icollection/) から正常に削除された場合は true、そうでない場合は false。このメソッドは、元の [ICollection](../../../system.collections.generic/icollection/) に *item* が見つからない場合も false を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [ParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)