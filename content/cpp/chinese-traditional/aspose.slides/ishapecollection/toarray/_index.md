---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並返回包含所有圖形的陣列。
type: docs
weight: 287
url: /zh-hant/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() 方法

建立並返回包含所有圖形的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### 傳回值

一個包含 [IShape](../../ishape/) 物件的陣列。

## IShapeCollection::ToArray(int32_t, int32_t) 方法

建立並返回包含指定範圍內所有圖形的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 要返回的第一個圖形的索引。 |
| count | **int32_t** | 要返回的圖形數量。 |

### 傳回值

一個包含 [IShape](../../ishape/) 物件的陣列。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)