---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Atomizuje zadaný řetězec a přidá jej do NameTable.
type: docs
weight: 14
url: /cs/system.xml/nametable/add/
---
## NameTable::Add(const String\&) method


Atomizuje zadaný řetězec a přidá jej do [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Řetězec, který se má přidat. |

### Návratová hodnota

Atomizovaný řetězec nebo existující řetězec, pokud již v [NameTable](../) existuje.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Atomizuje zadaný řetězec a přidá jej do [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Pole znaků obsahující řetězec, který se má přidat. |
| start | **int32_t** | Nulovým indexem do pole určujícím první znak řetězce. |
| len | **int32_t** | Počet znaků v řetězci. |

### Návratová hodnota

Atomizovaný řetězec nebo existující řetězec, pokud již v [NameTable](../) existuje. Pokud je **len** nula, vrátí se [String::Empty](../../../system/string/empty/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [NameTable](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)