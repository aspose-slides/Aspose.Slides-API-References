---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación textual de un número al entero sin signo de 64 bits equivalente.
type: docs
weight: 1
url: /es/system/uint64/parse/
---
## UInt64::Parse(const String\&) método


Convierte la cadena especificada que contiene la representación textual de un número al entero sin signo de 64 bits equivalente.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |

### Valor devuelto

El entero sin signo de 64 bits igual al número representado por la cadena especificada.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al entero sin signo de 64 bits equivalente usando la información de formato proporcionada.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |

### Valor devuelto

El entero sin signo de 64 bits igual al número representado por la cadena especificada.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Convierte la cadena especificada que contiene la representación textual de un número al entero sin signo de 64 bits equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual del número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |

### Valor devuelto

El entero sin signo de 64 bits igual al número representado por la cadena especificada.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ver también

* Enumeración [NumberStyles](../../../system.globalization/numberstyles/)
* Definición de tipo [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Estructura [UInt64](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)