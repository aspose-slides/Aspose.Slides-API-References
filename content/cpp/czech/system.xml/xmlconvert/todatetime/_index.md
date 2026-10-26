---
title: ToDateTime()
second_title: Aspose.Slides pro C++ referenci API
description: Převádí řetězec String na ekvivalent DateTime.
type: docs
weight: 417
url: /cs/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metoda


Převede [String](../../../system/string/) na ekvivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec, který se má převést. |

### Návratová hodnota

Ekvivalent [DateTime](../../../system/datetime/) řetězce.

## XmlConvert::ToDateTime(const String\&, const String\&) metoda


Převede [String](../../../system/string/) na ekvivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec, který se má převést. |
| format | const [String](../../../system/string/)\& | Formátová struktura, která se použije na převedený [DateTime](../../../system/datetime/). Platné formáty zahrnují "yyyy-MM-ddTHH:mm:sszzzzzz" a jeho podmnožiny. Řetězec je ověřen vůči tomuto formátu. |

### Návratová hodnota

Ekvivalent [DateTime](../../../system/datetime/) řetězce.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metoda


Převede [String](../../../system/string/) na ekvivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Řetězec, který se má převést. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Pole obsahující formátové struktury, které se použijí na převedený [DateTime](../../../system/datetime/). Platné formáty zahrnují "yyyy-MM-ddTHH:mm:sszzzzzz" a jeho podmnožiny. |

### Návratová hodnota

Ekvivalent [DateTime](../../../system/datetime/) řetězce.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metoda


Převede [String](../../../system/string/) na [DateTime](../../../system/datetime/) pomocí zadaného XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Hodnota [String](../../../system/string/) k převodu. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Jedna z hodnot výčtu, která určuje, zda má být datum převedeno na místní čas nebo zachováno jako koordinovaný světový čas (UTC), pokud se jedná o datum UTC. |

### Návratová hodnota

Ekvivalent [DateTime](../../../system/datetime/) [String](../../../system/string/).

## Viz také

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)