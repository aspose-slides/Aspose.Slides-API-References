---
title: DoTryFinally()
second_title: Referencia de API de Aspose.Slides para C++
description: La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción del traductor finally_statement_as_lambda establecida en true, la sentencia se traduce en la invocación de este método.
type: docs
weight: 2445
url: /es/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) función


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción del traductor finally_statement_as_lambda establecida en true, la sentencia se traduce a la invocación de este método.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## System::DoTryFinally(T\&&, F\&&) función


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción del traductor finally_statement_as_lambda establecida en true, la sentencia se traduce a la invocación de este método. Esta sobrecarga maneja el caso en que el valor de retorno del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally es bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## System::DoTryFinally(T\&&, F\&&) función


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción del traductor finally_statement_as_lambda establecida en true, la sentencia se traduce a la invocación de este método. Esta sobrecarga maneja el caso en que el valor de retorno del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally es bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)