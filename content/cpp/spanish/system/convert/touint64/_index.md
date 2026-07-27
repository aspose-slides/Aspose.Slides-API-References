---
title: ToUInt64()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero sin signo de 64 bits equivalente.
type: docs
weight: 196
url: /es/system/convert/touint64/
---
## Convert::ToUInt64(bool) método

Convierte el valor booleano especificado a un entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) método

Convierte el entero con signo de 8 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) método

Convierte el entero con signo de 16 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) método

Convierte el entero con signo de 32 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) método

Devuelve el entero sin signo de 64 bits especificado.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) método

Convierte el entero con signo de 64 bits especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) método

Convierte el número de tipo float especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) método

Convierte el número de tipo double especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) método

Convierte el número decimal especificado a un entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) método

Convierte el carácter Unicode especificado a un entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) método

Convierte la cadena nula especificada al valor entero sin signo de 64-bits equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Valor de retorno

Cero.

## Convert::ToUInt64(const char_t *) método


Convierte la c-cadena que contiene la representación textual de un número al valor entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-cadena a convertir |

### Valor de retorno

El valor entero sin signo de 64-bits igual al número representado por la c-cadena especificada

## Convert::ToUInt64(const String\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor de retorno

El valor entero sin signo de 64-bits igual al número representado por la cadena especificada

## Convert::ToUInt64(const String\&, int) método


Convierte la cadena que contiene la representación textual de un número en la base especificada al valor entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor de retorno

El valor entero sin signo de 64-bits igual al número representado por la cadena especificada

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero sin signo de 64-bits equivalente utilizando la información de formato proporcionada.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información del formato de cadena |

### Valor de retorno

El valor entero sin signo de 64-bits igual al número representado por la cadena especificada

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) método




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero sin signo de 64-bits equivalente utilizando la información de formato y el estilo numérico proporcionados.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual del número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información del formato de cadena |

### Valor de retorno

El valor entero sin signo de 64-bits igual al número representado por la cadena especificada

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) método 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) método 




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el valor empaquetado especificado a un valor entero sin signo de 64-bits equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que contiene el valor empaquetado a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor empaquetado es [String](../../string/) |

### Valor de retorno

Un valor entero sin signo de 64-bits equivalente al valor empaquetado especificado

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)