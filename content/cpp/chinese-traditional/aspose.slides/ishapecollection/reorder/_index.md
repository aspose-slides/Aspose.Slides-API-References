---
title: Reorder()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的形狀移動到形狀集合中的新位置。
type: docs
weight: 300
url: /zh-hant/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) 方法


將指定的形狀移動到形狀集合中的新位置。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based target index where the shape will be placed. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要在集合中移動的 [IShape](../../ishape/)。 |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) 方法


將指定的形狀在形狀集合中移動，從給定的索引開始放置它們。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based target index where the first specified shape will be placed; subsequent shapes follow in the order provided. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | 要在集合中移動的一個或多個 [IShape](../../ishape/) 實例。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)