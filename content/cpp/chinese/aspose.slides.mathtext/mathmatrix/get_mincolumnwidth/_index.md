---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API 参考
description: "最小列宽，以 twips 为单位（每点的 1/20）间隙间距（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth，以确定总的矩阵列间距（不同列相同边缘之间的距离）。默认值：0。"
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() 方法

最小列宽，以 twips 为单位（每点的 1/20） 间隙间距（亦称为 “Column Gap” 或 “Gap Width”）会加入 MinColumnWidth 以确定总的 Matrix [Column](../../../aspose.slides/column/) Spacing（不同列相同边缘之间的距离）。默认值：0。

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
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