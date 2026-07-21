---
title: get_DrawingGuides()
second_title: Aspose.Slides для C++ справочника API
description: Возвращает коллекцию направляющих для мастер слайда заметок. Только для чтения IDrawingGuidesCollection
type: docs
weight: 66
url: /ru/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() метод


Возвращает коллекцию направляющих для мастер слайда заметок. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [MasterNotesSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)