---
title: ToSingle()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un número de punto flotante de precisión simple equivalente.
type: docs
weight: 209
url: /es/system/convert/tosingle/
---
## Convert::ToSingle(bool) método

Convierte el valor booleano especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) método

Convierte el entero con signo de 8 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) método

Convierte el entero con signo de 16 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) método

Convierte el entero con signo de 32 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) método

Convierte el entero con signo de 64 bits especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) método

Devuelve el número float especificado.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) método

Convierte el número de doble precisión especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) método

Convierte el número decimal especificado a un número de punto flotante de precisión simple equivalente.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) método

Convierte la cadena nula especificada al valor de punto flotante de precisión simple equivalente.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Valor devuelto

Cero.

## Convert::ToSingle(const char_t *) método

Convierte la cadena C especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La cadena C a convertir |

### Valor devuelto

El valor de punto flotante de precisión simple igual al número representado por la cadena C especificada

## Convert::ToSingle(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor de punto flotante de precisión simple igual al número representado por la cadena especificada

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente usando la información de formato proporcionada.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor de punto flotante de precisión simple igual al número representado por la cadena especificada

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) método




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente usando la información de formato proporcionada y el estilo numérico.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena |

### Valor devuelto

El valor de punto flotante de precisión simple igual al número representado por la cadena especificada

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) método 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor encapsulado especificado a un valor de punto flotante de precisión simple.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que encapsula el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor encapsulado es [String](../../string/) |

### Valor devuelto

Un valor de punto flotante de precisión simple equivalente al valor encapsulado especificado

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)