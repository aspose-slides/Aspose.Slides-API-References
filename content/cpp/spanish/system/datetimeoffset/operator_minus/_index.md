---
title: operator-()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una nueva instancia de la clase DateTimeOffset que representa el valor de fecha y hora que es el resultado de la resta del intervalo de tiempo especificado del valor representado por el objeto actual.
type: docs
weight: 521
url: /es/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const method

Devuelve una nueva instancia de la clase [DateTimeOffset](../) que representa el valor de fecha y hora que es el resultado de la resta del intervalo de tiempo especificado del valor representado por el objeto actual.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervalo de tiempo a restar |

### Valor devuelto

Una nueva instancia de la clase [DateTimeOffset](../) que representa el valor de fecha y hora que es el resultado de la resta de **value** del valor representado por el objeto actual.

## DateTimeOffset::operator-(const DateTimeOffset\&) const method

Devuelve una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y el especificado.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Una instancia de la clase [DateTime](../../datetime/) que marca uno de los extremos del intervalo a calcular |

### Valor devuelto

Una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y **other**.

## Ver también

* Clase [DateTimeOffset](../)
* Clase [TimeSpan](../../timespan/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)