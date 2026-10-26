---
title: ToDateTime()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje String na równoważnik DateTime.
type: docs
weight: 417
url: /pl/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metoda

Konwertuje [String](../../../system/string/) na równoważnik [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg znaków do konwersji. |

### Wartość zwracana

Równoważnik [DateTime](../../../system/datetime/) ciągu znaków.

## XmlConvert::ToDateTime(const String\&, const String\&) metoda

Konwertuje [String](../../../system/string/) na równoważnik [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg znaków do konwersji. |
| format | const [String](../../../system/string/)\& | Struktura formatu stosowana do przekonwertowanego [DateTime](../../../system/datetime/). Poprawne formaty obejmują „yyyy-MM-ddTHH:mm:sszzzzzz” i ich podzbiory. Ciąg jest walidowany względem tego formatu. |

### Wartość zwracana

Równoważnik [DateTime](../../../system/datetime/) ciągu znaków.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metoda

Konwertuje [String](../../../system/string/) na równoważnik [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg znaków do konwersji. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Tablica zawierająca struktury formatów stosowane do przekonwertowanego [DateTime](../../../system/datetime/). Poprawne formaty obejmują „yyyy-MM-ddTHH:mm:sszzzzzz” i ich podzbiory. |

### Wartość zwracana

Równoważnik [DateTime](../../../system/datetime/) ciągu znaków.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metoda

Konwertuje [String](../../../system/string/) na [DateTime](../../../system/datetime/) przy użyciu określonego XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Wartość [String](../../../system/string/) do konwersji. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Jedna z wartości wyliczenia określająca, czy data ma być przekształcona na czas lokalny, czy zachowana jako Uniwersalny Czas Koordynowany (UTC), jeśli jest to data UTC. |

### Wartość zwracana

Równoważnik [DateTime](../../../system/datetime/) [String](../../../system/string/).

## Zobacz także

* Wyliczenie [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [DateTime](../../../system/datetime/)
* Klasa [String](../../../system/string/)
* Klasa [XmlConvert](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)