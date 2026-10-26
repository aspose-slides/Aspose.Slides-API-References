---
title: get_NoBreak()
second_title: Referencia de API de Aspose.Slides para C++
description: "Sin salto Esta propiedad especifica la propiedad \"unbreakable\" en el cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no está especificado, pueden producirse saltos dentro del cuadro. Predeterminado: true"
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() método


Sin salto Esta propiedad especifica la propiedad \"unbreakable\" en el cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no está especificado, pueden producirse saltos dentro del cuadro. Predeterminado: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Ver también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)