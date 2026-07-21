---
title: get_Brush()
second_title: Справочник API Aspose.Slides для C++
description: Получает Brush для IInkLine IInkBrush только для чтения.
type: docs
weight: 1
url: /ru/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() метод

Получает Brush для IInkLine [IInkBrush](../../iinkbrush/) только для чтения.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IInkBrush](../../iinkbrush/)
* Класс [IInkTrace](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)