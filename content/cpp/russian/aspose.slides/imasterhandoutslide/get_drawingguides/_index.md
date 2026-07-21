---
title: get_DrawingGuides()
second_title: Справочная документация API Aspose.Slides для C++
description: Возвращает коллекцию направляющих черчения для слайда справки мастера. Только для чтения IDrawingGuidesCollection
type: docs
weight: 14
url: /ru/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() метод


Возвращает коллекцию направляющих черчения для слайда справки мастера. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [IMasterHandoutSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)