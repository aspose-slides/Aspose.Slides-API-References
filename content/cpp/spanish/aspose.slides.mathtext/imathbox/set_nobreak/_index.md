---
title: set_NoBreak()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Sin salto. Esta propiedad especifica la propiedad \"unbreakable\" en el cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden ocurrir saltos dentro del cuadro. Valor predeterminado: true"
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) método


Sin salto. Esta propiedad especifica la propiedad \"unbreakable\" en el cuadro de objeto. Cuando es true, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden ocurrir saltos dentro del cuadro. Valor predeterminado: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Ver también

* Clase [IMathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)