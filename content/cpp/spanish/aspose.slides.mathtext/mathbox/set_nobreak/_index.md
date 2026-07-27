---
title: set_NoBreak()
second_title: Referencia de API de Aspose.Slides para C++
description: "Sin salto Esta propiedad especifica la propiedad \"unbreakable\" en el cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro del cuadro. Predeterminado: true"
type: docs
weight: 53
url: /es/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) method

No break Esta propiedad especifica la propiedad \"ininterrumpible\" del cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro del cuadro. Predeterminado: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Observaciones

Ejemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Véase también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)