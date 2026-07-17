---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API 参考
description: 获取 R1C1 样式的公式。
type: docs
weight: 79
url: /zh/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() 方法

获取 R1C1 样式的公式。

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## 备注


```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [ChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)