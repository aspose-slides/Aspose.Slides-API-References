---
title: TryParseExact()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la representación en cadena especificada de un valor de fecha y hora al objeto DateTime equivalente utilizando el formato especificado, la información de formato específica de la cultura y el estilo. El formato de la representación en cadena debe coincidir exactamente con el formato especificado.
type: docs
weight: 898
url: /es/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) método


Convierte la representación en cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente utilizando el formato especificado, la información de formato específica de la cultura y el estilo. El formato de la representación en cadena debe coincidir exactamente con el formato especificado.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un valor de fecha y hora a convertir. |
| format | const [String](../../string/)\& | El formato de cadena. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |
| result | [DateTime](../)\& | El argumento de salida que, si la conversión tiene éxito, contiene el resultado de la conversión. |

### Valor de retorno

True si la conversión tiene éxito, de lo contrario - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) método


Convierte la representación en cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente utilizando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación en cadena debe coincidir exactamente con uno o más de los formatos especificados.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un valor de fecha y hora a convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | La matriz de formatos de cadena. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |
| result | [DateTime](../)\& | El argumento de salida que, si la conversión tiene éxito, contiene el resultado de la conversión. |

### Valor de retorno

True si la conversión tiene éxito, de lo contrario - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Ver también

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)