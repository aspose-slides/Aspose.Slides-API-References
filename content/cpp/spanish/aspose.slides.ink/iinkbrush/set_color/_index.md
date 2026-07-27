---
title: set_Color()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el color del pincel para una línea.
type: docs
weight: 14
url: /es/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) método

Establece el color del pincel para una línea.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Ver también

* Clase [Color](../../../system.drawing/color/)
* Clase [IInkBrush](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)