---
title: set_MinColumnWidth()
second_title: Aspose.Slides C++ API 参考
description: "最小列宽（以 twips 为单位，1/20 点） 间隙（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth 上，以确定总 Matrix Column Spacing（不同列相同边缘之间的距离）。默认值：0。"
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) 方法


最小列宽（以 twips 为单位，1/20 点） 间隙（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth 上，以确定总 Matrix [Column](../../../aspose.slides/column/) Spacing（不同列相同边缘之间的距离）。默认值：0。

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## 备注


示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另请参见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)