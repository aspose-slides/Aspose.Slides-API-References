---
title: get_Overlap()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100% ~ 100%)로 지정합니다.
type: docs
weight: 183
url: /ko/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() 메서드

차트의 막대와 열이 2-D 차트에서 겹치는 정도를 백분율( -100% ~ 100% )로 지정합니다.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## 비고

* -100%: 최대 간격 (막대가 완전히 분리됩니다).
* 0%: 막대가 겹침이나 간격 없이 나란히 배치됩니다.
* 100%: 최대 겹침 (막대가 서로 완전히 겹칩니다). 이 속성은 읽기/쓰기 **int8_t**.

다음 예제는 차트 시리즈 그룹의 겹침을 설정하고 폼에 결과 차트를 렌더링하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 겹침을 55%로 설정

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## 관련 항목

* 클래스 [IChartSeriesGroup](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)