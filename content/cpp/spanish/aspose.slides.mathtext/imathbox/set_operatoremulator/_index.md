---
title: set_OperatorEmulator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Operator Emulator. Cuando es true, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Operator Emulators se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) método


Emulador de operador. Cuando es verdadero, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operadores se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Ver también

* Clase [IMathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)