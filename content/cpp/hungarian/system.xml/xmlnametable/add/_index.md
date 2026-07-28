---
title: Add()
second_title: Aspose.Slides C++ API Referenciája
description: Ha egy származtatott osztályban felülírják, atomizálja a megadott karakterláncot, és hozzáadja az XmlNameTable-hez.
type: docs
weight: 14
url: /hu/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) módszer

Amikor egy származtatott osztályban felülírják, atomizálja a megadott karakterláncot, és hozzáadja a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A név hozzáadásához használt karaktertömb. |
| offset | **int32_t** | A tömbben a név első karakterét megadó nullától indexelt pozíció. |
| length | **int32_t** | A név karaktereinek száma. |

### Visszatérési érték

Az új atomizált karakterlánc, vagy a már létező, ha már létezik. Ha a hossz 0, akkor [String::Empty](../../../system/string/empty/) kerül visszaadásra.

## XmlNameTable::Add(const String\&) módszer

Amikor egy származtatott osztályban felülírják, atomizálja a megadott karakterláncot, és hozzáadja a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | A hozzáadandó név. |

### Visszatérési érték

Az új atomizált karakterlánc, vagy a már létező, ha már létezik.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNameTable](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)