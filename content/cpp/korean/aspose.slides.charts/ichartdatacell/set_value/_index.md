---
title: set_Value()
second_title: Aspose.Slides for C++ API 참조
description: "셀의 값을 설정합니다. System::Object를 씁니다."
type: docs
weight: 40
url: /ko/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) method


셀의 값을 설정합니다. [System::Object](../../../system/object/)를 씁니다.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## 비고



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [IChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)