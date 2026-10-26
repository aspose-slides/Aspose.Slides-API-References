---
title: get_NoBreak()
second_title: Referencia de API de Aspose.Slides para C++
description: "Sin salto. Esta propiedad especifica la \"unbreakable\" property en la caja de objeto. Cuando es true, no se pueden producir saltos de línea dentro de la caja. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro de la caja. Default: true"
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() método


Sin salto. Esta propiedad especifica la "unbreakable" property en la caja de objeto. Cuando es true, no se pueden producir saltos de línea dentro de la caja. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro de la caja. Default: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
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