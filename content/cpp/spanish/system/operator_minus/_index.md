---
title: operator-()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula el número de días entre dos días de la semana.
type: docs
weight: 2172
url: /es/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) función


Calcula el número de días entre dos días de la semana.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | El minuendo |
| b | [DayOfWeek](../dayofweek/) | El sustraendo |

### Valor de retorno

El número de días entre los días laborables **a** y **b**; el valor devuelto es un número negativo si *va* después de ****

## System::operator-(const T\&, const Decimal\&) función


Devuelve una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la sustracción del valor representado por el objeto [Decimal](../decimal/) especificado del valor especificado.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const T\& | El valor del que se resta |
| d | const [Decimal](../decimal/)\& | El objeto [Decimal](../decimal/) que representa el valor restado |

### Valor de retorno

Una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es el resultado de la sustracción del valor representado por **d** de **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) función


Desconecta todas las devoluciones de llamada en el delegado de la mano derecha desde el final de la lista de devoluciones de llamada del delegado de la mano izquierda.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | El delegado del que se eliminarán las devoluciones de llamada. |
| rhv | MulticastDelegate\<T\> | El delegado cuyas devoluciones de llamada serán eliminadas. |

### Valor de retorno

Devuelve un delegado que contiene las devoluciones de llamada del valor de la mano izquierda, pero sin las de la mano derecha.

## System::operator-(const T1\&, const Nullable\<T2\>\&) función


Resta valores no anulables y anulables.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando izquierdo. |
| T2 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| some | const T1\& | Operando izquierdo. |
| other | const [Nullable](../nullable/)\<T2\>\& | Operando derecho. |

### Valor de retorno

Resultado de la sustracción.

## Ver también

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)