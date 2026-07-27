---
title: HolderInitializer
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta clase se usa para obtener una referencia persistente a la instancia del objeto, sea lvalue o rvalue. Para obtener tal referencia, use el método 'HoldIfTemporary', que tiene tres sobrecargas. Dos de ellas toman un rvalue como parámetro y simplemente devuelven la referencia a él. La tercera, en cambio, toma un lvalue como parámetro, crea una copia de puntero y luego devuelve la referencia a esa copia. Además, la clase tiene el método 'Hold' para retener el valor pasado incondicionalmente (se usa para copiar valores de variables locales en la pila o sus referencias hijas)
type: docs
weight: 1639
url: /es/system/holderinitializer/
---
## HolderInitializer estructura

Esta clase se usa para obtener una referencia persistente al instancia del objeto, sea lvalue o rvalue. Para obtener tal referencia, use el método 'HoldIfTemporary', que tiene tres sobrecargas. Dos de ellas toman un rvalue como parámetro y simplemente devuelven la referencia a él. La tercera, en cambio, toma un lvalue como parámetro, crea una copia de puntero y luego devuelve la referencia a esa copia. Además, la clase tiene el método 'Hold' para retener el valor pasado incondicionalmente (se usa para copiar valores de variables locales en la pila o sus referencias hijas)

```cpp
template<typename T,bool>class HolderInitializer
```

### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | El tipo del objeto que se va a retener. |
| R | True, si T es un tipo referencia ([SmartPtr](../smartptr/) specialization or [System::String](../string/) type), y se requiere realmente mantener referencias temporales, false - en caso contrario. |

## Métodos

| Method | Description |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Copia el lvalue pasado al holder, luego devuelve la referencia del holder. El llamador debe usar este método para retener el valor pasado incondicionalmente. |
| [HolderInitializer](./holderinitializer/)(T\&) | Inicializa la referencia del holder con la pasada. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Devuelve la referencia al rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Devuelve la referencia al rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Copia el lvalue pasado al holder, luego devuelve la referencia del holder. |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)