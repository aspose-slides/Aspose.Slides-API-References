---
title: get_Size()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el tamaño del pincel para una línea en puntos.
type: docs
weight: 27
url: /es/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() método


Obtiene el tamaño del pincel para una línea en puntos.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Ver también

* Clase [SizeF](../../../system.drawing/sizef/)
* Clase [IInkBrush](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)