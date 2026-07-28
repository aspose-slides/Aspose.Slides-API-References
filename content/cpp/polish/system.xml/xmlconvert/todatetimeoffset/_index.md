---
title: ToDateTimeOffset()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Konwertuje podany String na równoważnik DateTimeOffset.
type: docs
weight: 430
url: /pl/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metoda


Konwertuje podany [String](../../../system/string/) na równoważnik [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg do konwersji. Ciąg musi spełniać podzespół zaleceń W3C dotyczących typu XML dateTime. Więcej informacji znajduje się w sekcji [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specyfikacji XML [Schema](../../../system.xml.schema/). |

### Wartość zwracana

Równoważnik [DateTimeOffset](../../../system/datetimeoffset/) podanego ciągu.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metoda


Konwertuje podany [String](../../../system/string/) na równoważnik [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg do konwersji. |
| format | const [String](../../../system/string/)\& | Format, z którego konwertowany jest **s**. Parametr format może być dowolnym podzestawem zaleceń W3C dotyczących typu XML dateTime. Więcej informacji znajduje się w sekcji [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specyfikacji XML [Schema](../../../system.xml.schema/). Ciąg **s** jest weryfikowany pod kątem tego formatu. |

### Wartość zwracana

Równoważnik [DateTimeOffset](../../../system/datetimeoffset/) podanego ciągu.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metoda


Konwertuje podany [String](../../../system/string/) na równoważnik [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Ciąg do konwersji. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Tablica formatów, z których może być konwertowany **s**. Każdy format w **formats** może być dowolnym podzestawem zaleceń W3C dotyczących typu XML dateTime. Więcej informacji znajduje się w sekcji [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) specyfikacji XML [Schema](../../../system.xml.schema/). Ciąg **s** jest weryfikowany pod kątem jednego z tych formatów. |

### Wartość zwracana

Równoważnik [DateTimeOffset](../../../system/datetimeoffset/) podanego ciągu.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [DateTimeOffset](../../../system/datetimeoffset/)
* Klasa [String](../../../system/string/)
* Klasa [XmlConvert](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)