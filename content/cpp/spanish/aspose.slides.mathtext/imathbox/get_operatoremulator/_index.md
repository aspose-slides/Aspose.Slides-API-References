---
title: get_OperatorEmulator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Emulador de operador. Cuando es true, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto de interrupción de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() método

Emulador de operador. Cuando es true, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto de interrupción de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
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