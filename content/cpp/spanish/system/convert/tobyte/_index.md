---
title: ToByte()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero sin signo de 8 bits equivalente.
type: docs
weight: 92
url: /es/system/convert/tobyte/
---
## Convert::ToByte(bool) método

Convierte el valor booleano especificado a un entero sin signo de 8 bits equivalente.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) método

Devuelve el entero sin signo de 8 bits especificado.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) método

Convierte el entero con signo de 8 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) método

Convierte el entero con signo de 16 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) método

Convierte el entero con signo de 32 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) método

Convierte el entero con signo de 64 bits especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) método

Convierte el número de tipo float especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) método

Convierte el número de tipo double especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) método

Convierte el número decimal especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) método

Convierte el carácter Unicode especificado a un entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) método

La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) método

Convierte la cadena nula especificada al valor entero sin signo de 8 bits equivalente.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Valor devuelto

Cero.

## Convert::ToByte(const char_t *) método


Convierte la cadena C que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La cadena C a convertir |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena C especificada

## Convert::ToByte(const String\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena especificada

## Convert::ToByte(const String\&, int) método


Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena especificada

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente usando la información de formato proporcionada.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena especificada

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) método 




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enum NumberStyles que especifica el estilo permitido de la representación de cadena de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero sin signo de 8 bits igual al número representado por la cadena especificada

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) método 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) método 




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el valor encapsulado especificado a un valor entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que encapsula el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor encapsulado es [String](../../string/) |

### Valor devuelto

Un valor entero sin signo de 8 bits equivalente al valor encapsulado especificado

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [Decimal](../../decimal/)
* Clase [DateTime](../../datetime/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Clase [Object](../../object/)
* Estructura [Convert](../)
* Estructura [Enum](../../enum/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)