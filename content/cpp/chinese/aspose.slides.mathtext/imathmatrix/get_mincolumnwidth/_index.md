---
title: get_MinColumnWidth()
second_title: Aspose.Slides C++ API 参考
description: "以 twips 为单位的最小列宽 (1/20 点) 间隙间距 (也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D) 将加到 MinColumnWidth 上，以确定整个 Matrix Column Spacing（不同列相同边缘之间的距离）。默认: 0."
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() 方法

最小列宽，以 twips 为单位（1/20 点）。间隙间距（也称为 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）会加到 MinColumnWidth 上，以确定整个 Matrix [Column](../../../aspose.slides/column/) Spacing（不同列相同边缘之间的距离）。默认：0。

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另请参阅

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)