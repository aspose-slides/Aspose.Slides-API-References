---
title: ToBox()
second_title: Referencia de la API de Aspose.Slides para C++
description: Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro.
type: docs
weight: 274
url: /es/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() método


Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### Valor devuelto

Caja lógica con este elemento colocado dentro
## Observaciones



Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBox](../../imathbox/)
* Clase [IMathElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)