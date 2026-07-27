---
title: Subtract()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una nueva instancia de la clase DateTime que representa el valor de fecha y hora resultante de la sustracción del intervalo de tiempo especificado del valor representado por el objeto actual.
type: docs
weight: 326
url: /es/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const método

Devuelve una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora que es el resultado de la sustracción del intervalo de tiempo especificado del valor representado por el objeto actual.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Un intervalo de tiempo a restar |

### Valor devuelto

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora que es el resultado de la sustracción de **duration** del valor representado por el objeto actual.

## DateTime::Subtract(DateTime) const método

Devuelve una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y el objeto especificado.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DateTime](../) | Una instancia de la clase [DateTime](../) que marca uno de los extremos del intervalo a calcular |

### Valor devuelto

Una instancia de la clase [TimeSpan](../../timespan/) que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y **value**.

## Ver también

* Clase [DateTime](../)
* Clase [TimeSpan](../../timespan/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)