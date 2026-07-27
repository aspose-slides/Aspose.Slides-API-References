---
title: GetRect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de texto en la porción, incluidas las vacías.
type: docs
weight: 79
url: /es/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() método


Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de texto en la porción, incluidas las vacías.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Valor devuelto

Rectángulo que delimita la porción [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Observaciones



Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## Véase también

* Clase [RectangleF](../../../system.drawing/rectanglef/)
* Clase [IPortion](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)