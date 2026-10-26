---
title: ToDateTimeOffset()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den bereitgestellten String in ein DateTimeOffset-Äquivalent.
type: docs
weight: 430
url: /de/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) Methode


Konvertiert das bereitgestellte [String](../../../system/string/) in ein [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. Die Zeichenkette muss einem Teilbereich der W3C-Empfehlung für den XML dateTime-Typ entsprechen. Weitere Informationen finden Sie im Abschnitt [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) der XML [Schema](../../../system.xml.schema/)-Spezifikation. |

### Rückgabewert

Das [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent der bereitgestellten Zeichenkette.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) Methode


Konvertiert das bereitgestellte [String](../../../system/string/) in ein [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. |
| format | const [String](../../../system/string/)\& | Das Format, aus dem **s** konvertiert wird. Der Formatparameter kann einen beliebigen Teilbereich der W3C-Empfehlung für den XML dateTime-Typ darstellen. Weitere Informationen finden Sie im Abschnitt [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) der XML [Schema](../../../system.xml.schema/)-Spezifikation. Die Zeichenkette **s** wird anhand dieses Formats validiert. |

### Rückgabewert

Das [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent der bereitgestellten Zeichenkette.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) Methode


Konvertiert das bereitgestellte [String](../../../system/string/) in ein [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ein Array von Formaten, aus denen **s** konvertiert werden kann. Jeder Format in **formats** kann einen beliebigen Teilbereich der W3C-Empfehlung für den XML dateTime-Typ darstellen. Weitere Informationen finden Sie im Abschnitt [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) der XML [Schema](../../../system.xml.schema/)-Spezifikation. Die Zeichenkette **s** wird anhand eines dieser Formate validiert. |

### Rückgabewert

Das [DateTimeOffset](../../../system/datetimeoffset/)-Äquivalent der bereitgestellten Zeichenkette.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DateTimeOffset](../../../system/datetimeoffset/)
* Klasse [String](../../../system/string/)
* Klasse [XmlConvert](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)