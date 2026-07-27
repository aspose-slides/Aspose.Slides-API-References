---
title: ParseExact()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la representación de cadena especificada de un valor de fecha y hora al objeto DateTime equivalente usando el formato especificado y la información de formato específica de la cultura. El formato de la representación de cadena debe coincidir exactamente con el formato especificado. Lanza una excepción si la conversión falla.
type: docs
weight: 872
url: /es/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente usando el formato especificado y la información de formato específica de la cultura. El formato de la representación de cadena debe coincidir exactamente con el formato especificado. Lanza una excepción si la conversión falla.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |
| format | const [String](../../string/)\& | El formato de cadena. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |

### Valor devuelto

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente usando los formatos especificados, la información de formato específica de la cultura y el estilo. El formato de la representación de cadena debe coincidir exactamente con uno o más de los formatos especificados. Lanza una excepción si la conversión falla.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | La matriz de formatos de cadena. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |

### Valor devuelto

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Ver también

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Clase [DateTime](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)