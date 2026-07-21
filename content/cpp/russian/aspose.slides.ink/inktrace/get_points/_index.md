---
title: get_Points()
second_title: Справка API Aspose.Slides для C++
description: "Получает точки для IInkLine System::Drawing::PointF только для чтения."
type: docs
weight: 14
url: /ru/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() метод

Получает точки для IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Только для чтения.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
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

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [InkTrace](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)