---
title: get_Color()
second_title: Справочник API Aspose.Slides для C++
description: Получает цвет кисти для линии.
type: docs
weight: 1
url: /ru/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() метод


Получает цвет кисти для линии.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## См. также

* Класс [Color](../../../system.drawing/color/)
* Класс [InkBrush](../)
* Пространство имен [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)