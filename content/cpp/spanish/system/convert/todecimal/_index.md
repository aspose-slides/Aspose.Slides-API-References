---
title: ToDecimal()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un número decimal equivalente.
type: docs
weight: 235
url: /es/system/convert/todecimal/
---
## Convert::ToDecimal(bool) método


Convierte el valor booleano especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) método


Convierte el entero sin signo de 8 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) método


Convierte el entero con signo de 8 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) método


Convierte el entero sin signo de 16 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) método


Convierte el entero con signo de 16 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) método


Convierte el entero sin signo de 32 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) método


Convierte el entero con signo de 32 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) método


Convierte el entero sin signo de 64 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) método


Convierte el entero con signo de 64 bits especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) método


Convierte el número de tipo float especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) método


Convierte el número de tipo double especificado a un número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) método


Devuelve el número decimal especificado.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) método


Convierte la cadena nula especificada al valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Valor de retorno

Zero.

## Convert::ToDecimal(const char_t *) método


Convierte la c-cadena especificada que contiene la representación textual de un número al valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-cadena a convertir |

### Valor de retorno

El valor [Decimal](../../decimal/) igual al número representado por la c-cadena especificada

## Convert::ToDecimal(const String\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor de retorno

El valor [Decimal](../../decimal/) igual al número representado por la cadena especificada

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor equivalente [Decimal](../../decimal/) usando la información de formato proporcionada.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor de retorno

El valor [Decimal](../../decimal/) igual al número representado por la cadena especificada

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor equivalente [Decimal](../../decimal/) usando los estilos numéricos y la información de formato especificados.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor de retorno

El valor [Decimal](../../decimal/) igual al número representado por la cadena especificada

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el valor empaquetado especificado al valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que empaqueta el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor empaquetado es [String](../../string/) |

### Valor de retorno

El valor [Decimal](../../decimal/) equivalente al valor empaquetado especificado

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)