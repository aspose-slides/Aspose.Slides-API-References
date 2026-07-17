---
title: get_Formula()
second_title: Aspose.Slides for C++ API 参考
description: 获取 A1 样式的公式。
type: docs
weight: 53
url: /zh/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() 方法

获取 A1 样式的公式。

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## 备注



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [ChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)