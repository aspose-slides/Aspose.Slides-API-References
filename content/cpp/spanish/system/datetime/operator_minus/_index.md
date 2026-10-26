---
title: operator-()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una nueva instancia de la clase DateTime que representa el valor de fecha y hora que es el resultado de la sustracción del intervalo de tiempo especificado del valor representado por el objeto actual.
type: docs
weight: 651
url: /es/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const método


Devuelve una nueva instancia de la [DateTime](../) class que representa el valor de fecha y hora que es el resultado de la sustracción del intervalo de tiempo especificado del valor representado por el objeto actual.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervalo de tiempo a restar |

### Valor devuelto

Una nueva instancia de la [DateTime](../) class que representa el valor de fecha y hora que es el resultado de la sustracción de **value** del valor representado por el objeto actual.

## DateTime::operator-(DateTime) const método


Devuelve una instancia de la [TimeSpan](../../timespan/) class que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y el objeto especificado.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DateTime](../) | Una instancia de la [DateTime](../) class que marca un extremo del intervalo a calcular |

### Valor devuelto

Una instancia de la [TimeSpan](../../timespan/) class que representa el intervalo de tiempo entre los valores de fecha y hora representados por el objeto actual y **value**.

## Ver también

* Clase [DateTime](../)
* Clase [TimeSpan](../../timespan/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)