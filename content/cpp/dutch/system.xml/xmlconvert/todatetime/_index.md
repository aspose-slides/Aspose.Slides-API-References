---
title: ToDateTime()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de String naar een DateTime-equivalent.
type: docs
weight: 417
url: /nl/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) methode

Converteert de [String](../../../system/string/) naar een [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. |

### Retourwaarde

Een [DateTime](../../../system/datetime/) equivalent van de string.

## XmlConvert::ToDateTime(const String\&, const String\&) methode

Converteert de [String](../../../system/string/) naar een [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. |
| format | const [String](../../../system/string/)\& | De opmaakstructuur die moet worden toegepast op de geconverteerde [DateTime](../../../system/datetime/). Geldige opmaken omvatten "yyyy-MM-ddTHH:mm:sszzzzzz" en subsets ervan. De string wordt gevalideerd tegen deze opmaak. |

### Retourwaarde

Een [DateTime](../../../system/datetime/) equivalent van de string.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) methode

Converteert de [String](../../../system/string/) naar een [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De string om te converteren. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Een array met de opmaakstructuren die moeten worden toegepast op de geconverteerde [DateTime](../../../system/datetime/). Geldige opmaken omvatten "yyyy-MM-ddTHH:mm:sszzzzzz" en subsets ervan. |

### Retourwaarde

Een [DateTime](../../../system/datetime/) equivalent van de string.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) methode

Converteert de [String](../../../system/string/) naar een [DateTime](../../../system/datetime/) met de opgegeven XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | De [String](../../../system/string/) waarde om te converteren. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Een van de enumeratiewaarden die aangeven of de datum moet worden geconverteerd naar lokale tijd of behouden moet blijven als gecoördineerde wereldtijd (UTC), als het een UTC-datum is. |

### Retourwaarde

Een [DateTime](../../../system/datetime/) equivalent van de [String](../../../system/string/).

## Zie ook

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)