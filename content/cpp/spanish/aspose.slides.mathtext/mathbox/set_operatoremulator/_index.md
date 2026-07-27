---
title: set_OperatorEmulator()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Emulador de Operador. Cuando es true, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los Emuladores de Operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) método


Emulador de Operador. Cuando es true, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los Emuladores de Operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
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