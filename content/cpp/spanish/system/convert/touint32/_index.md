---
title: ToUInt32()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero sin signo de 32 bits equivalente.
type: docs
weight: 170
url: /es/system/convert/touint32/
---
## Convert::ToUInt32(bool) método

Convierte el valor booleano especificado a un entero sin signo de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) método

Convierte el entero con signo de 8 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) método

Convierte el entero con signo de 16 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) método

Devuelve el entero sin signo de 32 bits especificado.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) método

Convierte el entero con signo de 32 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) método

Convierte el entero con signo de 64 bits especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) método

Convierte el número de tipo float especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) método

Convierte el número de tipo double especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) método

Convierte el número decimal especificado a un entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) método

Convierte el carácter Unicode especificado a un entero sin signo de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) método

La conversión no está soportada. Siempre lanza InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) método

Convierte la cadena nula especificada al valor entero sin signo de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Valor devuelto

Cero.

## Convert::ToUInt32(const char_t *) método

Convierte la c-string especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-string a convertir |

### Valor devuelto

El valor entero sin signo de 32 bits igual al número representado por la c-string especificada.

## Convert::ToUInt32(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor entero sin signo de 32 bits igual al número representado por la cadena especificada.

## Convert::ToUInt32(const String\&, int) método

Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor devuelto

El valor entero sin signo de 32 bits igual al número representado por la cadena especificada.

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente usando la información de formato proporcionada.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor entero sin signo de 32 bits igual al número representado por la cadena especificada.

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente usando la información de formato y el estilo de número proporcionados.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor entero sin signo de 32 bits igual al número representado por la cadena especificada.

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) método

```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor empaquetado especificado a un valor entero sin signo de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que empaqueta el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor empaquetado es [String](../../string/) |

### Valor devuelto

Un valor entero sin signo de 32 bits equivalente al valor empaquetado especificado.

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