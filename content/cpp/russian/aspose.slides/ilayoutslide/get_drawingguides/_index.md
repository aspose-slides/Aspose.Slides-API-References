---
title: get_DrawingGuides()
second_title: Aspose.Slides для C++ справка по API
description: Возвращает коллекцию направляющих рисунка для макета слайда. Только для чтения IDrawingGuidesCollection
type: docs
weight: 79
url: /ru/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() метод


Возвращает коллекцию направляющих рисунка для макета слайда. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Замечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Добавление новой вертикальной направляющей рисунка слева от центра слайда
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [ILayoutSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)