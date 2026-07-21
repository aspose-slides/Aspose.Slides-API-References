---
title: get_DrawingGuides()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает коллекцию направляющих для рисования для главного слайда. Только для чтения IDrawingGuidesCollection
type: docs
weight: 105
url: /ru/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() метод

Возвращает коллекцию направляющих для рисования для главного слайда. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Примечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Добавление новой вертикальной направляющей рисунка справа от центра слайда
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [IMasterSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)