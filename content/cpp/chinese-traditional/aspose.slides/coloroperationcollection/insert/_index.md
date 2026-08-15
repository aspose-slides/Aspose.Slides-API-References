---
title: Insert()
second_title: Aspose.Slides C++ API 參考
description: 將新操作插入到集合中。
type: docs
weight: 79
url: /zh-hant/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) 方法

將新操作插入到集合中。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **int32_t** | 將插入操作的索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作類型。 |
| parameter | **float** | 操作的參數。 |

### 返回值

已插入的操作。

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) 方法

將新操作插入到集合中。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **int32_t** | 將插入操作的索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作類型。 |

### 返回值

已插入的操作。

## 另請參閱

* 列舉 [ColorTransformOperation](../../colortransformoperation/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IColorOperation](../../icoloroperation/)
* 類別 [ColorOperationCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)