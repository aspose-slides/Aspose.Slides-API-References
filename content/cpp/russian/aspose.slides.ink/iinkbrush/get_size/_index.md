---
title: get_Size()
second_title: Справочник API Aspose.Slides для C++
description: Получает размер кисти для линии в пунктах.
type: docs
weight: 27
url: /ru/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() метод


Получает размер кисти для линии в пунктах.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
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
* Пространство имен [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)