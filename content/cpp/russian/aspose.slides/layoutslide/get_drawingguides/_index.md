---
title: get_DrawingGuides()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает коллекцию направляющих черчения для макетного слайда. Только для чтения IDrawingGuidesCollection
type: docs
weight: 118
url: /ru/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() метод


Возвращает коллекцию направляющих черчения для макетного слайда. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Добавление новой вертикальной направляющей черчения слева от центра слайда
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [LayoutSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)