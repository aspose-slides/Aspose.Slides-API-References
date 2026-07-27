---
title: TryParse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la representación de cadena especificada de un valor de fecha y hora al objeto DateTime equivalente.
type: docs
weight: 885
url: /es/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) método

Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |
| result | [DateTime](../)\& | El argumento de salida que, si la conversión tiene éxito, contiene el resultado de la conversión. |

### Valor devuelto

True si la conversión tiene éxito, de lo contrario - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) método

Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente utilizando la información de formato específica de la cultura y el estilo especificados.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |
| result | [DateTime](../)\& | El argumento de salida que, si la conversión tiene éxito, contiene el resultado de la conversión. |

### Valor devuelto

True si la conversión tiene éxito, de lo contrario - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Ver también

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)