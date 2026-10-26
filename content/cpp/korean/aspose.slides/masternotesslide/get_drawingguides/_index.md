---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 마스터 노트 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 IDrawingGuidesCollection
type: docs
weight: 66
url: /ko/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() 메서드

마스터 노트 슬라이드에 대한 그리기 가이드의 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 클래스 [MasterNotesSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)