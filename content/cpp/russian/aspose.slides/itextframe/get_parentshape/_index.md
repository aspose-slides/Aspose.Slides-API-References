---
title: get_ParentShape()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape только для чтения IShape.
type: docs
weight: 66
url: /ru/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() метод

Возвращает родительскую форму или null, если родительский объект не реализует интерфейс [IShape](../../ishape/) только для чтения [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Примечания

Следующий пример кода демонстрирует
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [ITextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)