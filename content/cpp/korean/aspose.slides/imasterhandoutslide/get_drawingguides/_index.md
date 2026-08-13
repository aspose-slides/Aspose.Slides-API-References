---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 마스터 핸드아웃 슬라이드에 대한 그림 가이드 컬렉션을 반환합니다. 읽기 전용 IDrawingGuidesCollection
type: docs
weight: 14
url: /ko/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() 메서드


마스터 핸드아웃 슬라이드에 대한 그림 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 클래스 [IMasterHandoutSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)