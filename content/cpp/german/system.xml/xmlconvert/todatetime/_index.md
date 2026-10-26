---
title: ToDateTime()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den String in ein DateTime-Äquivalent.
type: docs
weight: 417
url: /de/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) Methode


Konvertiert das [String](../../../system/string/) in ein [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. |

### Rückgabewert

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## XmlConvert::ToDateTime(const String\&, const String\&) Methode


Konvertiert das [String](../../../system/string/) in ein [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. |
| format | const [String](../../../system/string/)\& | Die Formatstruktur, die auf das konvertierte [DateTime](../../../system/datetime/) angewendet werden soll. Gültige Formate umfassen "yyyy-MM-ddTHH:mm:sszzzzzz" und dessen Teilmengen. Die Zeichenkette wird anhand dieses Formats validiert. |

### Rückgabewert

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) Methode


Konvertiert das [String](../../../system/string/) in ein [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Die zu konvertierende Zeichenkette. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ein Array, das die Formatstrukturen enthält, die auf das konvertierte [DateTime](../../../system/datetime/) angewendet werden sollen. Gültige Formate umfassen "yyyy-MM-ddTHH:mm:sszzzzzz" und dessen Teilmengen. |

### Rückgabewert

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) Methode


Konvertiert das [String](../../../system/string/) in ein [DateTime](../../../system/datetime/) mithilfe des angegebenen XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Der [String](../../../system/string/)-Wert, der konvertiert werden soll. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Einer der Enumerationswerte, der angibt, ob das Datum in die lokale Zeit konvertiert oder als Coordinated Universal Time (UTC) beibehalten werden soll, falls es sich um ein UTC-Datum handelt. |

### Rückgabewert

Ein [DateTime](../../../system/datetime/) Äquivalent des [String](../../../system/string/).

## Siehe auch

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [String](../../../system/string/)
* Klasse [XmlConvert](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)