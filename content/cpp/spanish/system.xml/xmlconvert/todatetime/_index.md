---
title: ToDateTime()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el String a un equivalente DateTime.
type: docs
weight: 417
url: /es/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) método


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. |

### Valor de retorno

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## XmlConvert::ToDateTime(const String\&, const String\&) método


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. |
| format | const [String](../../../system/string/)\& | La estructura de formato que se aplicará al [DateTime](../../../system/datetime/) convertido. Los formatos válidos incluyen "yyyy-MM-ddTHH:mm:sszzzzzz" y sus subconjuntos. La cadena se valida contra este formato. |

### Valor de retorno

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) método


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La cadena a convertir. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Una matriz que contiene las estructuras de formato que se aplicarán al [DateTime](../../../system/datetime/) convertido. Los formatos válidos incluyen "yyyy-MM-ddTHH:mm:sszzzzzz" y sus subconjuntos. |

### Valor de retorno

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) método


Convierte el [String](../../../system/string/) a un [DateTime](../../../system/datetime/) usando el XmlDateTimeSerializationMode especificado.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | El valor [String](../../../system/string/) a convertir. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Uno de los valores de enumeración que especifican si la fecha debe convertirse a hora local o preservarse como Tiempo Universal Coordinado (UTC), si es una fecha UTC. |

### Valor de retorno

Un equivalente [DateTime](../../../system/datetime/) del [String](../../../system/string/).

## Véase también

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)