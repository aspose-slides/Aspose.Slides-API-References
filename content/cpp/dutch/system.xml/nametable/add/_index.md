---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Atomiseert de opgegeven tekenreeks en voegt deze toe aan de NameTable.
type: docs
weight: 14
url: /nl/system.xml/nametable/add/
---
## NameTable::Add(const String\&) methode

Atomiseert de opgegeven tekenreeks en voegt deze toe aan de [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | De tekenreeks die moet worden toegevoegd. |

### Retourwaarde

De geatomiseerde tekenreeks of de bestaande tekenreeks als deze al bestaat in de [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) methode

Atomiseert de opgegeven tekenreeks en voegt deze toe aan de [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | De tekenreeks met karakters die moet worden toegevoegd. |
| start | **int32_t** | De nulgebaseerde index in de array die het eerste teken van de tekenreeks aangeeft. |
| len | **int32_t** | Het aantal tekens in de tekenreeks. |

### Retourwaarde

De geatomiseerde tekenreeks of de bestaande tekenreeks als er al één bestaat in de [NameTable](../). Als **len** nul is, wordt [String::Empty](../../../system/string/empty/) geretourneerd.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [NameTable](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)