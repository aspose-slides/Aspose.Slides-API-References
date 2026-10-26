---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 레이블 리더 라인 형식을 나타냅니다. 읽기 전용 IChartLinesFormat.
type: docs
weight: 66
url: /ko/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() 메서드


데이터 레이블 리더 라인 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## 비고


예제: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartLinesFormat](../../ichartlinesformat/)
* 클래스 [DataLabelCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)