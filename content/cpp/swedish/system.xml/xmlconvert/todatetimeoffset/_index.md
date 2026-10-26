---
title: ToDateTimeOffset()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna String till en DateTimeOffset-motsvarighet.
type: docs
weight: 430
url: /sv/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metod


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) motsvarighet.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. Strängen måste följa ett delmängd av W3C:s rekommendation för XML dateTime-typen. För mer information, se [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime)-avsnittet i XML [Schema](../../../system.xml.schema/)-specifikationen. |

### Returvärde

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten för den angivna strängen.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metod


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) motsvarighet.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. |
| format | const [String](../../../system/string/)\& | Formatet som **s** konverteras från. Formatparametern kan vara en valfri delmängd av W3C:s rekommendation för XML dateTime-typen. För mer information, se [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime)-avsnittet i XML [Schema](../../../system.xml.schema/)-specifikationen. Strängen **s** valideras mot detta format. |

### Returvärde

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten för den angivna strängen.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metod


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) motsvarighet.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | En array av format som **s** kan konverteras från. Varje format i **formats** kan vara en valfri delmängd av W3C:s rekommendation för XML dateTime-typen. För mer information, se [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime)-avsnittet i XML [Schema](../../../system.xml.schema/)-specifikationen. Strängen **s** valideras mot ett av dessa format. |

### Returvärde

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten för den angivna strängen.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [DateTimeOffset](../../../system/datetimeoffset/)
* Klass [String](../../../system/string/)
* Klass [XmlConvert](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)