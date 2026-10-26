---
title: get_ParentShape()
second_title: Ссылка на API Aspose.Slides для C++
description: Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape. Только для чтения IShape.
type: docs
weight: 92
url: /ru/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() метод


Возвращает родительскую форму или null, если родительский объект не реализует интерфейс [IShape](../../ishape/). Только для чтения [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Примечания


Следующий пример кода показывает 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [TextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)