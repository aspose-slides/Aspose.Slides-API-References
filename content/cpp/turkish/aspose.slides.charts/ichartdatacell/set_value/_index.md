---
title: set_Value()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir hücrenin değerini ayarlar. System::Object yazın."
type: docs
weight: 40
url: /tr/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) metod


Bir hücrenin değerini ayarlar. Yazın [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## Açıklamalar



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [IChartDataCell](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)