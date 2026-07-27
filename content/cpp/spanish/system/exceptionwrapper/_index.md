---
title: ExceptionWrapper
second_title: Referencia de la API de Aspose.Slides para C++
description: Plantilla que representa un contenedor de excepciones derivadas de la clase Exception.
type: docs
weight: 833
url: /es/system/exceptionwrapper/
---
## ExceptionWrapper class

Plantilla que representa un contenedor de excepciones derivadas de la clase Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Métodos

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Construye una instancia nula de la clase [ExceptionWrapper](./) que no representa ninguna excepción. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Construye una instancia de la clase [ExceptionWrapper](./) que contiene el puntero pasado. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Constructor de copia. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Constructor de movimiento. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructor que reenvía los parámetros a los constructores de la clase Exception y crea un puntero inteligente que contiene una nueva instancia de la clase Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Operador de conversión implícito a SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Permite acceder a los miembros del objeto Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operador de asignación. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operador de asignación de movimiento. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Atajo para obtener el objeto [System::TypeInfo](../typeinfo/) del tipo Exception. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Usado para funciones de casting. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)