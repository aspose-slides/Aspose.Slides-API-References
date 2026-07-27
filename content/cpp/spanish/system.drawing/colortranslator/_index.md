---
title: ColorTranslator
second_title: Referencia de API de Aspose.Slides para C++
description: "Realiza traducciones de color. Los objetos de esta clase deben asignarse solo mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 66
url: /es/system.drawing/colortranslator/
---
## ColorTranslator clase

Realiza traducciones de color. Los objetos de esta clase deben asignarse solo mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que producirá errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ColorTranslator
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Convierte la representación de color HTML especificada al objeto [Color](../color/) equivalente. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Convierte el color [Windows](../../system.windows/) especificado al objeto [Color](../color/) equivalente. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Convierte el objeto [Color](../color/) especificado a la representación en cadena del color HTML equivalente. |
## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)