---
title: operator>()
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 2120
url: /es/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) función




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) función




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) función


Siempre devuelve false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) función


Determina si el valor especificado es mayor que el valor representado por el objeto [Nullable](../nullable/) especificado al aplicar [operator>()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del primer valor comparado |
| T2 | El tipo subyacente del objeto [Nullable](../nullable/) que representa el segundo valor comparado |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| some | const T1\& | Una referencia constante al valor que se usará como primer comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | El objeto [Nullable](../nullable/) cuyo valor representado se usará como segundo comparando |

### Valor devuelto

True si el primer comparando es mayor que el segundo comparando, de lo contrario - false

## System::operator>(std::nullptr_t, TimeSpan) función




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Ver también

* Clase [DateTime](../datetime/)
* Clase [DateTimeOffset](../datetimeoffset/)
* Clase [Nullable](../nullable/)
* Clase [TimeSpan](../timespan/)
* Estructura [IsNullable](../isnullable/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)