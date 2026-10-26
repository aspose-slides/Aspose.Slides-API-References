---
title: ToDateTime()
second_title: Aspose.Slides C++ API Referenciája
description: Átalakítja a String-et egy DateTime megfelelővé.
type: docs
weight: 417
url: /hu/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metódus

Átalakítja a [String](../../../system/string/)-t egy [DateTime](../../../system/datetime/) megfelelővé.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Az átalakítandó karakterlánc. |

### Visszatérési érték

Egy [DateTime](../../../system/datetime/) megfelelője a karakterláncnak.

## XmlConvert::ToDateTime(const String\&, const String\&) metódus

Átalakítja a [String](../../../system/string/)-t egy [DateTime](../../../system/datetime/) megfelelővé.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Az átalakítandó karakterlánc. |
| format | const [String](../../../system/string/)\& | A formátumstruktúra, amelyet az átalakított [DateTime](../../../system/datetime/)-re alkalmazunk. Érvényes formátumok közé tartozik a "yyyy-MM-ddTHH:mm:sszzzzzz" és annak részformái. A karakterlánc ellenőrzésre kerül ezzel a formátummal szemben. |

### Visszatérési érték

Egy [DateTime](../../../system/datetime/) megfelelője a karakterláncnak.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metódus

Átalakítja a [String](../../../system/string/)-t egy [DateTime](../../../system/datetime/) megfelelővé.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Az átalakítandó karakterlánc. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Egy tömb, amely a formátumstruktúrákat tartalmazza az átalakított [DateTime](../../../system/datetime/)-re való alkalmazáshoz. Érvényes formátumok közé tartozik a "yyyy-MM-ddTHH:mm:sszzzzzz" és annak részformái. |

### Visszatérési érték

Egy [DateTime](../../../system/datetime/) megfelelője a karakterláncnak.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metódus

Átalakítja a [String](../../../system/string/)-t egy [DateTime](../../../system/datetime/)-ra a megadott XmlDateTimeSerializationMode használatával.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A [String](../../../system/string/) érték, amelyet konvertálni kell. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Az enumeráció egyik értéke, amely meghatározza, hogy a dátumot helyi időre konvertáljuk-e, vagy UTC (Coordinated Universal Time) időként hagyjuk meg, ha az UTC dátum. |

### Visszatérési érték

Egy [DateTime](../../../system/datetime/) megfelelője a [String](../../../system/string/)-nek.

## Lásd még

* Enumeráció [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [String](../../../system/string/)
* Osztály [XmlConvert](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)