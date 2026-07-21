---
title: get_Points()
second_title: Справочник API Aspose.Slides для C++
description: "Получает точки для IInkLine System::Drawing::PointF только для чтения."
type: docs
weight: 14
url: /ru/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() метод

Получает точки для IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) только для чтения.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [IInkTrace](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)