---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 참조
description: 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 IDrawingGuidesCollection
type: docs
weight: 105
url: /ko/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() 메서드


마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// 슬라이드 중앙 오른쪽에 새로운 수직 그리기 가이드를 추가합니다
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 클래스 [IMasterSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)