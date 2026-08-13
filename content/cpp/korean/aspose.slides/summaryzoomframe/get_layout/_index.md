---
title: get_Layout()
second_title: Aspose.Slides for C++ API 참조
description: 프레임의 Summary Zoom 섹션 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.
type: docs
weight: 1
url: /ko/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() 메서드


프레임의 Summary Zoom 섹션 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## 비고


예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 참조

* Enum [ZoomLayout](../../zoomlayout/)
* 클래스 [SummaryZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)