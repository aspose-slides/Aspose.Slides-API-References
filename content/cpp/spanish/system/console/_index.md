---
title: Console
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona métodos para enviar datos al flujo de salida estándar. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 196
url: /es/system/console/
---
## Console clase

Proporciona métodos para enviar datos al flujo de salida estándar. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Console
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [Beep](./beep/)() | NO IMPLEMENTADO. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Devuelve un puntero compartido que apunta al objeto que representa el flujo de error estándar. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Devuelve un puntero compartido que apunta al objeto que representa el flujo de entrada estándar. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Devuelve un puntero compartido que apunta al objeto que representa el flujo de salida estándar. |
| static void [Mute](./mute/)(**bool**) | Silencia o reactiva el flujo de salida estándar. |
| static void [ReadKey](./readkey/)() | NO IMPLEMENTADO. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Establece el título de la ventana de consola. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Asigna el objeto especificado a la propiedad Error de la clase. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Establece la propiedad In al objeto TextReader especificado. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Asigna el objeto especificado a la propiedad Out de la clase. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Envía la representación en cadena del objeto especificado al flujo de salida estándar. |
| static void [Write](./write/)(**bool**) | Envía la representación en cadena del valor bool al flujo de salida estándar. |
| static void [Write](./write/)(char_t) | Envía el valor de carácter especificado al flujo de salida estándar. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Envía la representación en cadena del arreglo de caracteres especificado al flujo de salida estándar. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Envía la representación en cadena del valor [Decimal](../decimal/) al flujo de salida estándar. |
| static void [Write](./write/)(**double**) | Envía la representación en cadena del valor de punto flotante de doble precisión al flujo de salida estándar. |
| static void [Write](./write/)(**float**) | Envía la representación en cadena del valor de punto flotante de precisión simple al flujo de salida estándar. |
| static void [Write](./write/)(**int32_t**) | Envía la representación en cadena del valor entero de 32 bits al flujo de salida estándar. |
| static void [Write](./write/)(**int64_t**) | Envía la representación en cadena del valor entero de 64 bits al flujo de salida estándar. |
| static void [Write](./write/)(const [String](../string/)\&) | Envía el objeto string especificado al flujo de salida estándar. |
| static void [Write](./write/)(const char_t *) | Envía la c-string especificada al flujo de salida estándar. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Envía la representación en cadena del valor [TypeInfo](../typeinfo/) al flujo de salida estándar. |
| static void [Write](./write/)(**uint32_t**) | Envía la representación en cadena del valor entero sin signo de 32 bits al flujo de salida estándar. |
| static void [Write](./write/)(**uint64_t**) | Envía la representación en cadena del valor entero sin signo de 64 bits al flujo de salida estándar. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Envía la representación en cadena del rango especificado del arreglo de caracteres especificado al flujo de salida estándar. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Envía la representación en cadena de los argumentos especificados formateados según el formato especificado al flujo de salida estándar. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Envía el terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Envía la representación en cadena del objeto especificado seguida del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**bool**) | Envía la representación en cadena del valor bool seguida del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(char_t) | Envía el carácter especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Envía la representación en cadena del arreglo de caracteres especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Envía la representación en cadena del valor [Decimal](../decimal/) seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**double**) | Envía la representación en cadena del valor de doble precisión seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**float**) | Envía la representación en cadena del valor de precisión simple seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**int32_t**) | Envía la representación en cadena del valor entero de 32 bits seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**int64_t**) | Envía la representación en cadena del valor entero de 64 bits seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Envía el objeto string especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const char_t *) | Envía la c-string especificada seguida del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Envía la representación en cadena del valor [TypeInfo](../typeinfo/) seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Envía la representación en cadena del valor entero sin signo de 32 bits seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Envía la representación en cadena del valor entero sin signo de 64 bits seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Envía la representación en cadena del rango especificado del arreglo de caracteres especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Envía la representación en cadena del objeto Exception especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Envía la representación en cadena de los argumentos especificados formateados según el formato especificado seguido del terminador de línea actual al flujo de salida estándar. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Observaciones



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Imprime el mensaje de saludo.
  Console::WriteLine(u"Hello, world!");

  // Crea una instancia de la clase 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Imprime los elementos del arreglo.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Hello, world!
1 2 3 4 5
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)