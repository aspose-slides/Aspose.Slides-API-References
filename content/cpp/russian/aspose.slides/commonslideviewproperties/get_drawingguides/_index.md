---
title: get_DrawingGuides()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию направляющих черчения. Только для чтения IDrawingGuidesCollection
type: docs
weight: 53
url: /ru/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() метод

Возвращает коллекцию направляющих черчения. Только для чтения [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Примечания

Следующий пример кода показывает, как добавить новые направляющие черчения в презентацию PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Класс [CommonSlideViewProperties](../)
* Простойство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)