---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 將新操作插入集合中。
type: docs
weight: 40
url: /zh-hant/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) 方法

將新操作插入集合中。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **int32_t** | 將插入操作之索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作類型。 |
| parameter | **float** | 操作的參數。 |

### 傳回值

已插入的操作。

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) 方法

將新操作插入集合中。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **int32_t** | 將插入操作之索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作類型。 |

### 傳回值

已插入的操作。

## 另請參閱

* 列舉 [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IColorOperation](../../icoloroperation/)
* 類別 [IColorOperationCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)