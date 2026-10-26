---
title: get_OperatorEmulator()
second_title: "Referencia de la API de Aspose.Slides para C++"
description: "Emulador de operador. Cuando es verdadero, la caja y su contenido se comportan como un solo operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() método

Emulador de operador. Cuando es verdadero, la caja y su contenido se comportan como un solo operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Observaciones

Ejemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Ver también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)