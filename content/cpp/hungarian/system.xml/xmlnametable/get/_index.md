---
title: Get()
second_title: Aspose.Slides C++ API-referencia
description: Ha egy leszármazott osztályban felül van írva, visszaadja az atomizált karakterláncot, amely ugyanazokat a karaktereket tartalmazza, mint a megadott tömbben a meghatározott karaktertartomány.
type: docs
weight: 1
url: /hu/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metódus


Egy leszármazott osztályban felülírva visszaadja az atomizált karakterláncot, amely ugyanazokat a karaktereket tartalmazza, mint a megadott tömbben a megadott karaktertartomány.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A karaktertömb, amely a keresendő nevet tartalmazza. |
| offset | **int32_t** | A tömbön belüli nulláralapú index, amely a név első karakterét jelöli. |
| length | **int32_t** | A név karaktereinek száma. |

### Visszatérési érték

Az atomizált karakterlánc vagy **nullptr**, ha a karakterlánc még nem lett atomizálva. Ha **length** nulla, akkor [String::Empty](../../../system/string/empty/) kerül visszaadásra.

## XmlNameTable::Get(const String\&) metódus


Egy leszármazott osztályban felülírva visszaadja az atomizált karakterláncot, amely megegyezik a megadott karakterlánc értékével.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | A keresendő név. |

### Visszatérési érték

Az atomizált karakterlánc vagy **nullptr**, ha a karakterlánc még nem lett atomizálva.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNameTable](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)