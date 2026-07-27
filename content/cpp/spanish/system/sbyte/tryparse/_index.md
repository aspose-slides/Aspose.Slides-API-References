---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente.
type: docs
weight: 14
url: /es/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) método

Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| result | **int8_t**\& | La referencia a una variable de entero con signo de 8 bits donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) método

Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente usando la información de formato y el estilo de número proporcionados.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |
| result | **int8_t**\& | La referencia a una variable de entero con signo de 8 bits donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) método

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) método

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) método

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)