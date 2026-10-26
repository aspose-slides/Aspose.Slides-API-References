---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 참조
description: 그리기 가이드의 컬렉션을 반환합니다. 읽기 전용 IDrawingGuidesCollection
type: docs
weight: 53
url: /ko/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() 메서드


그리기 가이드의 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## 비고


다음 샘플 코드는 PowerPoint 프레젠테이션에 새 그리기 가이드를 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// 슬라이드 중앙 오른쪽에 새로운 수직 그리기 가이드를 추가합니다
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// 슬라이드 중앙 아래에 새로운 수평 그리기 가이드를 추가합니다
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 클래스 [CommonSlideViewProperties](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)