---
title: ToDateTime()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar String till en DateTime-motsvarighet.
type: docs
weight: 417
url: /sv/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metod

Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/) motsvarighet.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. |

### Returvärde

En [DateTime](../../../system/datetime/) motsvarighet av strängen.

## XmlConvert::ToDateTime(const String\&, const String\&) metod

Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/) motsvarighet.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. |
| format | const [String](../../../system/string/)\& | Formatstrukturen som ska tillämpas på den konverterade [DateTime](../../../system/datetime/). Giltiga format inkluderar "yyyy-MM-ddTHH:mm:sszzzzzz" och dess delmängder. Strängen valideras mot detta format. |

### Returvärde

En [DateTime](../../../system/datetime/) motsvarighet av strängen.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metod

Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/) motsvarighet.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Strängen att konvertera. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | En array som innehåller formatstrukturerna som ska tillämpas på den konverterade [DateTime](../../../system/datetime/). Giltiga format inkluderar "yyyy-MM-ddTHH:mm:sszzzzzz" och dess delmängder. |

### Returvärde

En [DateTime](../../../system/datetime/) motsvarighet av strängen.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metod

Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/) med den specificerade XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Värdet [String](../../../system/string/) som ska konverteras. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Ett av enumerationsvärdena som anger om datumet ska konverteras till lokal tid eller bevaras som koordinerad universell tid (UTC), om det är ett UTC-datum. |

### Returvärde

En [DateTime](../../../system/datetime/) motsvarighet av [String](../../../system/string/).

## Se även

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* klass [DateTime](../../../system/datetime/)
* klass [String](../../../system/string/)
* klass [XmlConvert](../)
* namnrymd [System::Xml](../../)
* bibliotek [Aspose.Slides](../../../)