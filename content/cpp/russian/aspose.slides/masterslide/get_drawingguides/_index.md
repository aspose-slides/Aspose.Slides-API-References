---
title: get_DrawingGuides()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает коллекцию направляющих черчения для главного слайда. Только для чтения IDrawingGuidesCollection
type: docs
weight: 170
url: /ru/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() метод

Возвращает коллекцию направляющих черчения для главного слайда. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Примечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Добавление новой вертикальной направляющей черчения справа от центра слайда
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [MasterSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)