---
title: get_Layout()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레임에서 Summary Zoom 섹션의 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.
type: docs
weight: 1
url: /ko/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() 메서드


프레임에서 Summary Zoom 섹션의 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## 비고


이 예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 참조

* Enum [ZoomLayout](../../zoomlayout/)
* 클래스 [ISummaryZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)