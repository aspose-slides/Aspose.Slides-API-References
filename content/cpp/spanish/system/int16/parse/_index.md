---
title: Parse()
second_title: Aspose.Slides para la referencia de API de C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente.
type: docs
weight: 1
url: /es/system/int16/parse/
---
## Int16::Parse(const String\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |

### Valor devuelto

El entero con signo de 16 bits igual al número representado por la cadena especificada.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente usando la información de formato proporcionada.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El entero con signo de 16 bits igual al número representado por la cadena especificada.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) método




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente usando la información de formato y el estilo de número proporcionados.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enum NumberStyles que especifica el estilo permitido de la representación en forma de cadena de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El entero con signo de 16 bits igual al número representado por la cadena especificada.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Véase también

* Enumeración [NumberStyles](../../../system.globalization/numberstyles/)
* Definición de tipo [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Int16](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)