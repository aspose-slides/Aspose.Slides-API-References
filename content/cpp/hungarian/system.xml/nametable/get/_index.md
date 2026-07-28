---
title: Get()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a megadott értékkel rendelkező atomizált karakterláncot.
type: docs
weight: 27
url: /hu/system.xml/nametable/get/
---
## NameTable::Get(const String\&) metódus


Visszaadja az adott értékkel rendelkező atomizált karakterláncot.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A keresendő név. |

### Visszatérési érték

Az atomizált karakterlánc objektum, vagy **nullptr**, ha a karakterlánc még nincs atomizálva.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metódus


Visszaadja az atomizált karakterláncot, amely ugyanazokat a karaktereket tartalmazza, mint a megadott karaktertartomány a megadott tömbben.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A keresendő nevet tartalmazó karaktertömb. |
| start | **int32_t** | A tömbben a név első karakterét megadó nullától kezdődő index. |
| len | **int32_t** | A név karaktereinek száma. |

### Visszatérési érték

Az atomizált karakterlánc vagy **nullptr**, ha a karakterlánc még nincs atomizálva. Ha **len** nulla, akkor [String::Empty](../../../system/string/empty/) kerül visszaadásra.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [NameTable](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)