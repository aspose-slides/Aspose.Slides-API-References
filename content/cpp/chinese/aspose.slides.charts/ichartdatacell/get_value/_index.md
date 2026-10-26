---
title: get_Value()
second_title: Aspose.Slides C++ API 参考
description: "获取单元格的值。阅读 System::Object。"
type: docs
weight: 27
url: /zh/aspose.slides.charts/ichartdatacell/get_value/
---
## IChartDataCell::get_Value() 方法

获取单元格的值。阅读 [System::Object](../../../system/object/)。

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Charts::IChartDataCell::get_Value()=0
```

## 备注


```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [IChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)