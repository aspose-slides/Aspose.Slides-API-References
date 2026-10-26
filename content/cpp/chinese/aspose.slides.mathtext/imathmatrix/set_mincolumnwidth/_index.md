---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API 参考
description: "twips（1/20 点）中的最小列宽。间距（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth 上，以确定总的 Matrix 列间距（不同列相同边缘之间的距离）。默认值：0。"
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) 方法

列的最小宽度，以 twip 为单位（1/20 点）。间距（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth 上，以确定总的 Matrix [Column](../../../aspose.slides/column/) 间距（不同列相同边缘之间的距离）。默认值：0。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## 备注

示例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另请参阅

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)