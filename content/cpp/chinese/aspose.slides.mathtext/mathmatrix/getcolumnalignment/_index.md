---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定列的水平对齐方式
type: docs
weight: 248
url: /zh/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) 方法

获取指定列的水平对齐方式

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 零基列索引 |

### 返回值

指定列的水平对齐方式
## 备注



示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 另请参见

* 枚举 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)