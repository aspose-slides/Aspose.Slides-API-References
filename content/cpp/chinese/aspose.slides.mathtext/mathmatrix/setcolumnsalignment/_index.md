---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API 参考
description: 设置指定列的水平对齐方式
type: docs
weight: 274
url: /zh/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) 方法

设置指定列的水平对齐方式

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | Zero-based index of the first column to set alignment |
| columnsCount | **uint32_t** | The number of columns to specify the alignment |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | New value of horizontal alignment of specified column |
## 备注



示例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 另见

* 枚举 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)