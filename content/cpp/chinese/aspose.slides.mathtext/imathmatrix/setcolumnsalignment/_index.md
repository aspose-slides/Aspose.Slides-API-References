---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API 参考
description: 设置指定列的水平对齐方式
type: docs
weight: 261
url: /zh/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) 方法

设置指定列的水平对齐方式

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 设置对齐的第一列的零基索引 |
| columnsCount | **uint32_t** | 指定对齐的列数 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定列的水平对齐的新值 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 另见

* 枚举 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)