---
title: get_DrawingGuides()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию направляющих рисования. Только для чтения IDrawingGuidesCollection
type: docs
weight: 53
url: /ru/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() метод

Возвращает коллекцию направляющих рисования. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Примечания

Следующий пример кода показывает, как добавить новые направляющие рисования в презентацию PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Добавление новой вертикальной направляющей рисования справа от центра слайда
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Добавление новой горизонтальной направляющей рисования ниже центра слайда
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [ICommonSlideViewProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)