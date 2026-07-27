---
title: ToInt32()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un entero con signo de 32 bits equivalente.
type: docs
weight: 157
url: /es/system/convert/toint32/
---
## Convert::ToInt32(bool) método


Convierte el valor boolean especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) método


Convierte el entero sin signo de 8 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) método


Convierte el entero con signo de 8 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) método


Convierte el entero sin signo de 16 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) método


Convierte el entero con signo de 16 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) método


Convierte el entero sin signo de 32 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) método


Devuelve el entero con signo de 32 bits especificado.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) método


Convierte el entero sin signo de 64 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) método


Convierte el entero con signo de 64 bits especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) método


Convierte el número de punto flotante especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) método


Convierte el número doble especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) método


Convierte el número decimal especificado a un entero con signo de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) método


Convierte el carácter Unicode especificado a un entero con signo de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) método


La conversión no está soportada. Siempre lanza InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) método


Convierte la cadena nula especificada al valor entero de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```


### Valor devuelto

Cero.

## Convert::ToInt32(const char_t *) método


Convierte la c-cadena que contiene la representación textual de un número al valor entero de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-cadena a convertir |

### Valor devuelto

El valor entero de 32 bits igual al número representado por la c-cadena especificada

## Convert::ToInt32(const String\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor entero de 32 bits igual al número representado por la cadena especificada

## Convert::ToInt32(const String\&, int) método


Convierte la cadena que contiene la representación textual de un número en la base especificada al valor entero de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| from_base | int | La base del número representado por la cadena |

### Valor devuelto

El valor entero de 32 bits igual al número representado por la cadena especificada

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero de 32 bits equivalente utilizando la información de formato proporcionada.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero de 32 bits igual al número representado por la cadena especificada

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) método




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena que contiene la representación textual de un número al valor entero de 32 bits equivalente utilizando la información de formato y el estilo numérico proporcionados.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual del número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor entero de 32 bits igual al número representado por la cadena especificada

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método 




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) método 




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) método 




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el valor encapsulado especificado a un valor entero de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que encapsula el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor encapsulado es [String](../../string/) |

### Valor devuelto

Un valor entero de 32 bits equivalente al valor encapsulado especificado

## See Also

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