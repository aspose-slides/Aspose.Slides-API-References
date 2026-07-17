---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API 参考
description: 设置指定列的水平对齐
type: docs
weight: 261
url: /zh/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) 方法

设置指定列的水平对齐

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 零基列索引 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定列的水平对齐的新值 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 参见

* 枚举 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)