---
title: ToInt64()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero con signo de 64 bits equivalente.
type: docs
weight: 183
url: /es/system/convert/toint64/
---
## Convert::ToInt64(bool) método

Convierte el valor booleano especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```
## Convert::ToInt64(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```
## Convert::ToInt64(int8_t) método

Convierte el entero con signo de 8 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```
## Convert::ToInt64(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```
## Convert::ToInt64(int16_t) método

Convierte el entero con signo de 16 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```
## Convert::ToInt64(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```
## Convert::ToInt64(int32_t) método

Convierte el entero con signo de 32 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```
## Convert::ToInt64(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un entero con signo de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```
## Convert::ToInt64(int64_t) método

Devuelve el entero con signo de 64 bits especificado.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```
## Convert::ToInt64(float) método

Convierte el número de punto flotante especificado a un entero con signo de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(float value)
```
## Convert::ToInt64(double) método

Convierte el número double especificado a un entero con signo de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(double value)
```
## Convert::ToInt64(const Decimal\&) método

Convierte el número decimal especificado a un entero con signo de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```
## Convert::ToInt64(char_t) método

Convierte el carácter Unicode especificado a un entero con signo de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```
## Convert::ToInt64(DateTime) método

No se admite la conversión. Siempre lanza InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```
## Convert::ToInt64(std::nullptr_t) método

Convierte la cadena nula especificada al valor entero de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Valor devuelto

Cero.

## Convert::ToInt64(const char_t *) método

Convierte la c-string especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-string a convertir |

### Valor devuelto

El valor entero de 64 bits igual al número representado por la c-string especificada

## Convert::ToInt64(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor entero de 64 bits igual al número representado por la cadena especificada

## Convert::ToInt64(const String\&, int) método

Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor devuelto

El valor entero de 64 bits igual al número representado por la cadena especificada

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente usando la información de formato proporcionada.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero de 64 bits igual al número representado por la cadena especificada

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente usando la información de formato proporcionada y el estilo numérico.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero de 64 bits igual al número representado por la cadena especificada

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) método




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor boxed especificado a un valor entero de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que contiene el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor boxed es [String](../../string/) |

### Valor devuelto

Un valor entero de 64 bits equivalente al valor boxed especificado

## Véase también

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