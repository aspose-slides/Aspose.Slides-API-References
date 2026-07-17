---
title: get_R1C1Formula()
second_title: Aspose.Slides C++ API 参考
description: 获取 R1C1 样式的公式。
type: docs
weight: 79
url: /zh/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() 方法


获取 R1C1 样式的公式。

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## 备注



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 参见

* 类 [String](../../../system/string/)
* 类 [IChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)