---
title: set_Value()
second_title: Aspose.Slides for C++ API 参考
description: "设置单元格的值。写入 System::Object."
type: docs
weight: 40
url: /zh/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) 方法

设置单元格的值。写入[System::Object](../../../system/object/)。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## 备注



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [IChartDataCell](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)