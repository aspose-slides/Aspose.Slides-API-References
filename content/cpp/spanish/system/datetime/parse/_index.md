---
title: Parse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la representación de cadena especificada de un valor de fecha y hora al objeto DateTime equivalente.
type: docs
weight: 859
url: /es/system/datetime/parse/
---
## DateTime::Parse(const String\&) método

Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |

### Valor de retorno

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) método

Convierte la representación de cadena especificada de un valor de fecha y hora al objeto [DateTime](../) equivalente utilizando información de formato específica de cultura.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación de cadena de un valor de fecha y hora a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona información de formato específica de cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinación bit a bit de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [DateTime](../). |

### Valor de retorno

Una nueva instancia de la clase [DateTime](../) que representa el valor de fecha y hora equivalente al representado por la cadena especificada.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) método




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) método




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) método




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Véase también

* Enumeración [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [DateTime](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)