---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 32-bit equivalente.
type: docs
weight: 1
url: /es/system/int32/parse/
---
## Int32::Parse(const String\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 32 bits equivalente.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |

### Valor devuelto

El entero con signo de 32 bits igual al número representado por la cadena especificada.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 32 bits usando la información de formato proporcionada.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |

### Valor devuelto

El entero con signo de 32 bits igual al número representado por la cadena especificada.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) método

```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 32 bits usando la información de formato y el estilo de número proporcionados.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación a nivel de bits de los valores del enum NumberStyles que especifica el estilo permitido de la representación en cadena de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |

### Valor devuelto

El entero con signo de 32 bits igual al número representado por la cadena especificada.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) método

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) método

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Int32](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Clase [ReadOnlySpan](../../readonlyspan/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)