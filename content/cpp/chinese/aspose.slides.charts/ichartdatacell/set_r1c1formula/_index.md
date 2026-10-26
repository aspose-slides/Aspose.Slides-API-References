---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API 参考
description: 以 R1C1 样式设置公式。
type: docs
weight: 92
url: /zh/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) 方法


以 R1C1 样式设置公式。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## 备注



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [IChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)