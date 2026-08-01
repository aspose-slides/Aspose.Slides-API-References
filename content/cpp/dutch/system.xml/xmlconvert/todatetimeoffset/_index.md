---
title: ToDateTimeOffset()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven String naar een DateTimeOffset-equivalent.
type: docs
weight: 430
url: /nl/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) methode


Converteert de aangeleverde [String](../../../system/string/) naar een [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. De string moet voldoen aan een subset van de W3C Recommendation voor het XML dateTime-type. Voor meer informatie, zie de [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) sectie van de XML [Schema](../../../system.xml.schema/) specificatie. |

### Retourwaarde

Het [DateTimeOffset](../../../system/datetimeoffset/) equivalent van de aangeleverde string.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) methode


Converteert de aangeleverde [String](../../../system/string/) naar een [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. |
| format | const [String](../../../system/string/)\& | Het formaat waarvan **s** wordt geconverteerd. De formatparameter kan elke subset van de W3C Recommendation voor het XML dateTime-type zijn. Voor meer informatie, zie de [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) sectie van de XML [Schema](../../../system.xml.schema/) specificatie. De string **s** wordt gevalideerd tegen dit formaat. |

### Retourwaarde

Het [DateTimeOffset](../../../system/datetimeoffset/) equivalent van de aangeleverde string.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) methode


Converteert de aangeleverde [String](../../../system/string/) naar een [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Een array van formaten waaruit **s** kan worden geconverteerd. Elk formaat in **formats** kan elke subset van de W3C Recommendation voor het XML dateTime-type zijn. Voor meer informatie, zie de [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) sectie van de XML [Schema](../../../system.xml.schema/) specificatie. De string **s** wordt gevalideerd tegen een van deze formaten. |

### Retourwaarde

Het [DateTimeOffset](../../../system/datetimeoffset/) equivalent van de aangeleverde string.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DateTimeOffset](../../../system/datetimeoffset/)
* Klasse [String](../../../system/string/)
* Klasse [XmlConvert](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)