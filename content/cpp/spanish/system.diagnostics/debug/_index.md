---
title: Debug
second_title: Referencia de API de Aspose.Slides para C++
description: Colección de métodos de depuración que permiten enviar información de depuración a los oyentes registrados. Todas las funciones de salida funcionan solo en Debug. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 105
url: /es/system.diagnostics/debug/
---
## Estructura de depuración

Colección de métodos de depuración que permiten enviar información de depuración a los oyentes registrados. Todas las funciones de salida funcionan solo en [Debug](./). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Debug
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Comprueba la condición y envía información en caso de fallo. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Comprueba la condición y envía información en caso de fallo. |
| static void [Assert](./assert/)(**bool**, const char *) | Comprueba la condición y envía información en caso de fallo. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Comprueba la condición y envía información en caso de fallo. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Enviar mensaje de error. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Accede a la lista estática de oyentes. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Imprime mensaje en la interfaz de depuración. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Imprime mensaje en la interfaz de depuración. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Escribe cadena en la interfaz de depuración. |
| static void [Write](./write/)(const char_t *) | Escribe cadena en la interfaz de depuración. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Escribe cadena en la interfaz de depuración si una condición es verdadera. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Escribe línea en la interfaz de depuración. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe línea en la interfaz de depuración. |
| static void [WriteLine](./writeline/)(const char_t *) | Escribe línea en la interfaz de depuración. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escribe línea en la interfaz de depuración. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Escribe línea en la interfaz de depuración si una condición es verdadera. |

## Véase también

* Espacio de nombres [System::Diagnostics](../)
* Biblioteca [Aspose.Slides](../../)