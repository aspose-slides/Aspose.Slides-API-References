---
title: Interlocked
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona una API para operaciones seguras en hilos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 131
url: /es/system.threading/interlocked/
---
## Clase Interlocked

Proporciona una API para operaciones seguras en hilos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Interlocked
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Incrementa el valor de forma atómica. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Incrementa el valor de forma atómica. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. No implementado. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Decrementa el valor de forma atómica. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Decrementa el valor de forma atómica. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. No implementado. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Incrementa el valor de forma atómica mediante el procedimiento de intercambio-suma. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Incrementa el valor de forma atómica mediante el procedimiento de intercambio-suma. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Incrementa el valor de forma atómica. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Incrementa el valor de forma atómica. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Devuelve un valor de 64 bits, cargado como una operación atómica. |

## Ver también

* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)