---
title: Add()
second_title: Aspose.Slides C++ API hivatkozása
description: Atomizálja a megadott karakterláncot, és hozzáadja a NameTable-hez.
type: docs
weight: 14
url: /hu/system.xml/nametable/add/
---
## NameTable::Add(const String\&) metódus


Atomizálja a megadott karakterláncot, és hozzáadja a [NameTable](../)-hez.

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | A hozzáadandó karakterlánc. |

### Visszatérési érték

Az atomizált karakterlánc vagy a már létező karakterlánc, ha már létezik a [NameTable](../)-ban.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metódus


Atomizálja a megadott karakterláncot, és hozzáadja a [NameTable](../)-hez.

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A karaktertömb, amely a hozzáadandó karakterláncot tartalmazza. |
| start | **int32_t** | A tömbben a karakterlánc első karakterét meghatározó nullától induló index. |
| len | **int32_t** | A karakterlánc karaktereinek száma. |

### Visszatérési érték

Az atomizált karakterlánc vagy a már létező karakterlánc, ha már létezik a [NameTable](../)-ban. Ha **len** nulla, akkor [String::Empty](../../../system/string/empty/) kerül visszaadásra.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [NameTable](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)