---
title: set_Overlap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100%까지)로 지정합니다.
type: docs
weight: 196
url: /ko/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) 메서드


2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% 사이)로 지정합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## 비고


* -100%: 최대 간격(막대가 완전히 분리됩니다).
* 0%: 막대가 겹치거나 간격 없이 나란히 배치됩니다.
* 100%: 최대 겹침(막대가 서로 완전히 겹칩니다). 이 속성은 읽기/쓰기 **int8_t**입니다.



다음 예제는 차트 시리즈 그룹의 겹침을 설정하고 결과 차트를 폼에 렌더링하는 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 겹침을 55%로 설정

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## 참조

* 클래스 [IChartSeriesGroup](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)