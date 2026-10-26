---
title: ToDateTimeOffset()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott String-et egy DateTimeOffset megfelelővé.
type: docs
weight: 430
url: /hu/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metódus


Átalakítja a megadott [String](../../../system/string/)-t egy [DateTimeOffset](../../../system/datetimeoffset/) megfelelővé.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A konvertálandó karakterlánc. A karakterláncnak meg kell felelnie az XML dateTime típusra vonatkozó W3C ajánlás egy részhalmazának. További információért tekintse meg a [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) szakaszt az XML [Schema](../../../system.xml.schema/) specifikációban. |

### Visszatérési érték

A megadott karakterlánc [DateTimeOffset](../../../system/datetimeoffset/) megfelelője.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metódus


Átalakítja a megadott [String](../../../system/string/)-t egy [DateTimeOffset](../../../system/datetimeoffset/) megfelelővé.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A konvertálandó karakterlánc. |
| format | const [String](../../../system/string/)\& | Az a formátum, amelyből a **s** konvertálva van. A formátum paraméter lehet a W3C ajánlás az XML dateTime típusra vonatkozó bármely részhalmaza. További információért tekintse meg a [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) szakaszt az XML [Schema](../../../system.xml.schema/) specifikációban. A **s** karakterlánc ellenőrzésre kerül ezzel a formátummal szemben. |

### Visszatérési érték

A megadott karakterlánc [DateTimeOffset](../../../system/datetimeoffset/) megfelelője.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metódus


Átalakítja a megadott [String](../../../system/string/)-t egy [DateTimeOffset](../../../system/datetimeoffset/) megfelelővé.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A konvertálandó karakterlánc. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Formátumok tömbje, amelyből a **s** konvertálható. Minden formátum a **formats**-ban a W3C ajánlás az XML dateTime típusra vonatkozó bármely részhalmaza lehet. További információért tekintse meg a [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) szakaszt az XML [Schema](../../../system.xml.schema/) specifikációban. A **s** karakterlánc ellenőrzésre kerül valamelyik formátumnál. |

### Visszatérési érték

A megadott karakterlánc [DateTimeOffset](../../../system/datetimeoffset/) megfelelője.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)