---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトの最初の出現を ICollection から削除します。
type: docs
weight: 339
url: /ja/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) メソッド

特定のオブジェクトの最初の出現を [ICollection](../../../system.collections.generic/icollection/) から削除します。

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | [ICollection](../../../system.collections.generic/icollection/) から削除するオブジェクト。 |

### 戻り値

*item* が [ICollection](../../../system.collections.generic/icollection/) から正常に削除された場合は true、そうでない場合は false。このメソッドは *item* が元の [ICollection](../../../system.collections.generic/icollection/) に見つからない場合も false を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IImageTransformOperation](../../iimagetransformoperation/)
* クラス [ImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)