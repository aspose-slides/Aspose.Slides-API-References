---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考
description: "取得儲存格的值。閱讀 System::Object."
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/chartdatacell/get_value/
---
## ChartDataCell::get_Value() 方法

取得儲存格的值。閱讀 [System::Object](../../../system/object/)。

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Charts::ChartDataCell::get_Value() override
```

## 備註

```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [ChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)