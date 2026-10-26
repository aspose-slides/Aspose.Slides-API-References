---
title: get_Count()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. Solo lectura int32_t.
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() método


Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. Solo lectura **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Observaciones


Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Ver también

* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)