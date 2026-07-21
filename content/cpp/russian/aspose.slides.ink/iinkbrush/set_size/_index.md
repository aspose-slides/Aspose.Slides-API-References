---
title: set_Size()
second_title: Aspose.Slides для C++ справка API
description: Устанавливает размер кисти для линии в пунктах.
type: docs
weight: 40
url: /ru/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) метод

Устанавливает размер кисти для линии в пунктах.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## См. также

* Класс [SizeF](../../../system.drawing/sizef/)
* Класс [IInkBrush](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)