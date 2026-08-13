---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 참조
description: 레이아웃 슬라이드에 대한 드로잉 가이드 컬렉션을 반환합니다. 읽기 전용 IDrawingGuidesCollection
type: docs
weight: 79
url: /ko/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() 메서드

레이아웃 슬라이드에 대한 드로잉 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// 슬라이드 중앙 왼쪽에 새로운 수직 드로잉 가이드를 추가합니다
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 클래스 [ILayoutSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)