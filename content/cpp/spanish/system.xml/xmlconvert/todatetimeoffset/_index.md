---
title: ToDateTimeOffset()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el String suministrado a su equivalente DateTimeOffset.
type: docs
weight: 430
url: /es/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) método

Convierte el [String](../../../system/string/) proporcionado a su equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. La cadena debe ajustarse a un subconjunto de la Recomendación W3C para el tipo de fecha y hora XML. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la especificación XML [Schema](../../../system.xml.schema/). |

### Valor devuelto

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) método

Convierte el [String](../../../system/string/) proporcionado a su equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. |
| format | const [String](../../../system/string/)\& | El formato a partir del cual se convierte **s**. El parámetro de formato puede ser cualquier subconjunto de la Recomendación W3C para el tipo de fecha y hora XML. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la especificación XML [Schema](../../../system.xml.schema/). La cadena **s** se valida contra este formato. |

### Valor devuelto

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) método

Convierte el [String](../../../system/string/) proporcionado a su equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Una matriz de formatos a partir de los cuales se puede convertir **s**. Cada formato en **formats** puede ser cualquier subconjunto de la Recomendación W3C para el tipo de fecha y hora XML. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la especificación XML [Schema](../../../system.xml.schema/). La cadena **s** se valida contra uno de estos formatos. |

### Valor devuelto

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [DateTimeOffset](../../../system/datetimeoffset/)
* Clase [String](../../../system/string/)
* Clase [XmlConvert](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)