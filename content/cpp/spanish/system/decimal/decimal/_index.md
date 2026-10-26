---
title: Decimal()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia que representa 0.
type: docs
weight: 1
url: /es/system/decimal/decimal/
---
## Decimal::Decimal() constructor


Construye una instancia que representa 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::int8_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::int8_t | Valor entero de 8 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::int16_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::int16_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::int16_t | Valor entero de 16 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::int32_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::int32_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::int32_t | Valor entero de 32 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::int64_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::int64_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::int64_t | Valor entero de 64 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::uint8_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::uint8_t | Valor entero sin signo de 8 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::uint16_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::uint16_t | Valor entero sin signo de 16 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::uint32_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::uint32_t | Valor entero sin signo de 32 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(std::uint64_t) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | std::uint64_t | Valor entero sin signo de 64 bits que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(float) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(float f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | **float** | El valor de punto flotante de precisión simple que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(double) constructor


Construye una instancia que representa el valor especificado.

```cpp
System::Decimal::Decimal(double d)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | **double** | El valor de punto flotante de doble precisión que será representado por el objeto [Decimal](../) que se está construyendo |

## Decimal::Decimal(const std::string\&) constructor


Construye una instancia que representa un valor cuya representación en cadena se especifica como una instancia de la clase std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) constructor


Construye un objeto [Decimal](../) a partir de los componentes especificados.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lo | **int32_t** | Los 32 bits bajos del valor |
| mid | **int32_t** | Los 32 bits intermedios del valor |
| hi | **int32_t** | Los 32 bits altos del valor |
| isNegative | **bool** | Especifica si el valor es negativo |
| scale | **uint8_t** | Una potencia de 10 que varía de 0 a 28 |

## Decimal::Decimal(const Decimal\&) constructor


Construye una instancia de la clase [Decimal](../) que representa el mismo número que el objeto [Decimal](../) especificado.

```cpp
System::Decimal::Decimal(const Decimal &d)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../)\& | Un objeto [Decimal](../) del cual copiar el valor |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) constructor


Construye una instancia de la clase [Decimal](../) a partir de una matriz de enteros que contiene una representación binaria.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Una matriz de enteros que contiene una representación binaria. |

## Decimal::Decimal(std::nullptr_t) constructor


Siempre lanza ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) constructor


Construye una instancia de la clase [Decimal](../) que representa el valor especificado.

```cpp
System::Decimal::Decimal(const number_type &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Una referencia constante al valor que será representado por el objeto que se está construyendo |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Clase [Decimal](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)