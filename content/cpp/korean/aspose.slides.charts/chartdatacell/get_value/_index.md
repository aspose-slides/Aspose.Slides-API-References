---
title: get_Value()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "셀의 값을 가져옵니다. System::Object를 읽어보세요."
type: docs
weight: 27
url: /ko/aspose.slides.charts/chartdatacell/get_value/
---
## ChartDataCell::get_Value() 메서드


셀의 값을 가져옵니다. [System::Object](../../../system/object/)를 읽어보세요.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Charts::ChartDataCell::get_Value() override
```

## 비고



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)