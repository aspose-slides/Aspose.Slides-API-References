---
title: Parse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 8 bits equivalente.
type: docs
weight: 1
url: /es/system/byte/parse/
---
## Byte::Parse(const String\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 8 bits equivalente.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |

### Valor devuelto

El entero sin signo de 8 bits equivalente al número representado por la cadena especificada.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 8 bits equivalente utilizando la información de formato proporcionada.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El entero sin signo de 8 bits equivalente al número representado por la cadena especificada.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) método

```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 8 bits equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación en forma de cadena de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El entero sin signo de 8 bits equivalente al número representado por la cadena especificada.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Byte](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)