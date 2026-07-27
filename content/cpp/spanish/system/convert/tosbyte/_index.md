---
title: ToSByte()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero con signo de 8 bits equivalente.
type: docs
weight: 105
url: /es/system/convert/tosbyte/
---
## Convert::ToSByte(bool) método

Convierte el valor booleano especificado a un entero con signo de 8 bits equivalente.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```
## Convert::ToSByte(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```
## Convert::ToSByte(int8_t) método

Devuelve el entero con signo de 8 bits especificado.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```
## Convert::ToSByte(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```
## Convert::ToSByte(int16_t) método

Convierte el entero con signo de 16 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```
## Convert::ToSByte(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```
## Convert::ToSByte(int32_t) método

Convierte el entero con signo de 32 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```
## Convert::ToSByte(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```
## Convert::ToSByte(int64_t) método

Convierte el entero con signo de 64 bits especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```
## Convert::ToSByte(float) método

Convierte el número de tipo float especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(float value)
```
## Convert::ToSByte(double) método

Convierte el número de tipo double especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(double value)
```
## Convert::ToSByte(const Decimal\&) método

Convierte el número decimal especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```
## Convert::ToSByte(char_t) método

Convierte el carácter Unicode especificado a un entero con signo de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```
## Convert::ToSByte(DateTime) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```
## Convert::ToSByte(std::nullptr_t) método

Convierte la cadena nula especificada al valor entero de 8 bits equivalente.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Valor devuelto

Cero.

## Convert::ToSByte(const char_t *) método

Convierte la c-cadena especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-cadena a convertir |

### Valor devuelto

El valor entero de 8 bits igual al número representado por la c-cadena especificada

## Convert::ToSByte(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor entero de 8 bits igual al número representado por la cadena especificada

## Convert::ToSByte(const String\&, int) método

Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor devuelto

El valor entero de 8 bits igual al número representado por la cadena especificada

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente usando la información de formato proporcionada.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor entero de 8 bits igual al número representado por la cadena especificada

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enum NumberStyles que especifica el estilo permitido de la representación textual del número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena especificada

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) método

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor empaquetado especificado al valor entero de 8 bits equivalente.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que encapsula el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor empaquetado es [String](../../string/) |

### Valor devuelto

Un valor entero de 8 bits equivalente al valor empaquetado especificado

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