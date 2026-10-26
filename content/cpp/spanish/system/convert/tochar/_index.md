---
title: ToChar()
second_title: Aspose.Slides for C++ Referencia de API
description: La conversión no es compatible. Siempre lanza InvalidCastException.
type: docs
weight: 118
url: /es/system/convert/tochar/
---
## Convert::ToChar(bool) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) método


Convierte el entero sin signo de 8 bits especificado a un carácter unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) método


Convierte el entero con signo de 8 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) método


Convierte el entero sin signo de 16 bits especificado a un carácter unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) método


Convierte el entero con signo de 16 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) método


Convierte el entero sin signo de 32 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) método


Convierte el entero con signo de 32 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) método


Convierte el entero sin signo de 64 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) método


Convierte el entero con signo de 64 bits especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) método


Devuelve el carácter unicode especificado.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) método


La conversión no es compatible. Siempre lanza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) método


Convierte el primer y único carácter de la c-string especificada a un valor char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-string a convertir; se espera que la c-string tenga exactamente 1 carácter. |

### Valor devuelto

El primer y único carácter de la c-string especificada si tiene exactamente 1 carácter de longitud, de lo contrario - 0

## Convert::ToChar(const String\&) método


Convierte el primer y único carácter de la cadena especificada a un valor char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir; se espera que la cadena tenga exactamente 1 carácter. |

### Valor devuelto

El primer y único carácter de la cadena especificada si tiene exactamente 1 carácter de longitud, de lo contrario - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el primer y único carácter de la cadena especificada a un valor char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir; se espera que la cadena tenga exactamente 1 carácter. |

### Valor devuelto

El primer y único carácter de la cadena especificada si tiene exactamente 1 carácter de longitud, de lo contrario - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte el valor boxed especificado a un carácter unicode equivalente.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El puntero compartido al objeto que encierra el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor encajado es [String](../../string/) |

### Valor devuelto

Un carácter unicode equivalente al valor encajado especificado

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