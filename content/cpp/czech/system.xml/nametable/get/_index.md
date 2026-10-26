---
title: Get()
second_title: Aspose.Slides pro C++ API referenci
description: Vrací atomizovaný řetězec se zadanou hodnotou.
type: docs
weight: 27
url: /cs/system.xml/nametable/get/
---
## NameTable::Get(const String\&) metoda


Vrací atomizovaný řetězec se zadanou hodnotou.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Název, který se má najít. |

### Návratová hodnota

Objekt atomizovaného řetězce nebo **nullptr**, pokud řetězec ještě nebyl atomizován.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda


Vrací atomizovaný řetězec obsahující stejné znaky jako zadaný rozsah znaků v daném poli.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Pole znaků obsahující název, který se má najít. |
| start | **int32_t** | Nulově založený index do pole určující první znak názvu. |
| len | **int32_t** | Počet znaků v názvu. |

### Návratová hodnota

Atomizovaný řetězec nebo **nullptr**, pokud řetězec ještě nebyl atomizován. Pokud je **len** nula, je vráceno [String::Empty](../../../system/string/empty/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [NameTable](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)