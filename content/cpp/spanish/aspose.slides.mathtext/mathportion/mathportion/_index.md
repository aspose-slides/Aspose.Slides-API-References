---
title: MathPortion()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase MathPortion.
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() constructor


Inicializa una nueva instancia de la clase [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```
## Observaciones


Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```
## Ver también

* Clase [MathPortion](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)