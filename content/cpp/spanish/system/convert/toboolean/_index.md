---
title: ToBoolean()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor booleano especificado.
type: docs
weight: 79
url: /es/system/convert/toboolean/
---
## Convert::ToBoolean(bool) método

Devuelve el valor booleano especificado.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) método

Convierte el entero con signo de 8 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) método

Convierte el entero con signo de 16 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) método

Convierte el entero con signo de 32 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) método

Convierte el entero con signo de 64 bits especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) método

Convierte el número de punto flotante especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) método

Convierte el número de doble precisión especificado a un valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) método

Convierte el número decimal especificado a un valor booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) método

Convierte la cadena nula especificada al valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Valor de retorno

False.

## Convert::ToBoolean(const char_t *) método

Convierte la cadena C especificada al valor de tipo bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La cadena C a convertir |

### Valor de retorno

True si la cadena C especificada es igual a "True" y false si la cadena C especificada es igual a "False".

## Convert::ToBoolean(const String\&) método

Convierte la cadena especificada al valor de tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor de retorno

True si la cadena C especificada es igual a "True" y false si la cadena especificada es igual a "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada al valor de tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor de retorno

True si la cadena C especificada es igual a "True" y false si la cadena especificada es igual a "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor empaquetado especificado a un valor booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que empaqueta el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor empaquetado es [String](../../string/) |

### Valor de retorno

Un valor booleano equivalente al valor empaquetado especificado

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)