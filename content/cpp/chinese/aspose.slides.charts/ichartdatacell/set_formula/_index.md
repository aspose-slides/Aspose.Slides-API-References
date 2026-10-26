---
title: set_Formula()
second_title: Aspose.Slides C++ API 参考
description: 以 A1 样式设置公式。
type: docs
weight: 66
url: /zh/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) 方法


以 A1 样式设置公式。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## 备注



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [IChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)