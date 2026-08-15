---
title: ToArray()
second_title: Aspose.Slides C++ API 參考
description: 建立並返回包含所有圖形的陣列。
type: docs
weight: 326
url: /zh-hant/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() 方法

Creates and returns an array that contains all shapes.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### 返回值

An array of [IShape](../../ishape/) objects.

## ShapeCollection::ToArray(int32_t, int32_t) 方法

Creates and returns an array that contains all shapes in the specified range.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | The index of the first shape to return. |
| count | **int32_t** | The number of shapes to return. |

### 返回值

An array of [IShape](../../ishape/) objects.

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)