---
title: Reorder()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的圖形移動到圖形集合中的新位置。
type: docs
weight: 339
url: /zh-hant/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) 方法

將指定的圖形移動到圖形集合中的新位置。

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 圖形將被放置的零基目標索引。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要在集合中移動的 [IShape](../../ishape/)。 |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) 方法

將指定的多個圖形在圖形集合中移動，從給定的索引開始依序放置。

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 第一個指定圖形將被放置的零基目標索引；其後的圖形將按提供的順序依次放置。 |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | 要在集合中移動的一個或多個 [IShape](../../ishape/) 實例。 |

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IShape](../../ishape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)