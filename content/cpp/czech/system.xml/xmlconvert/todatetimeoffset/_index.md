---
title: ToDateTimeOffset()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí dodaný String na ekvivalent DateTimeOffset.
type: docs
weight: 430
url: /cs/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metoda


Převede dodaný [String](../../../system/string/) na ekvivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec k převodu. Řetězec musí odpovídat podmnožině doporučení W3C pro typ XML dateTime. Pro více informací viz sekce [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specifikace XML [Schema](../../../system.xml.schema/). |

### Návratová hodnota

Ekvivalent [DateTimeOffset](../../../system/datetimeoffset/) dodaného řetězce.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metoda


Převede dodaný [String](../../../system/string/) na ekvivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec k převodu. |
| format | const [String](../../../system/string/)\& | Formát, ze kterého je **s** převáděn. Parametr formát může být libovolná podmnožina doporučení W3C pro typ XML dateTime. Pro více informací viz sekce [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specifikace XML [Schema](../../../system.xml.schema/). Řetězec **s** je ověřen vůči tomuto formátu. |

### Návratová hodnota

Ekvivalent [DateTimeOffset](../../../system/datetimeoffset/) dodaného řetězce.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metoda


Převede dodaný [String](../../../system/string/) na ekvivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec k převodu. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Pole formátů, ze kterých může být **s** převáděn. Každý formát v **formats** může být libovolná podmnožina doporučení W3C pro typ XML dateTime. Pro více informací viz sekce [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specifikace XML [Schema](../../../system.xml.schema/). Řetězec **s** je ověřen vůči jednomu z těchto formátů. |

### Návratová hodnota

Ekvivalent [DateTimeOffset](../../../system/datetimeoffset/) dodaného řetězce.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [DateTimeOffset](../../../system/datetimeoffset/)
* Třída [String](../../../system/string/)
* Třída [XmlConvert](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)