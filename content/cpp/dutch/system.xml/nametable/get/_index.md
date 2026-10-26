---
title: Get()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de geatomiseerde string met de opgegeven waarde.
type: docs
weight: 27
url: /nl/system.xml/nametable/get/
---
## NameTable::Get(const String\&) methode


Retourneert de geatomiseerde string met de opgegeven waarde.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De naam om te vinden. |

### Retourwaarde

Het geatomiseerde stringobject of **nullptr** als de string nog niet eerder is geatomiseerd.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) methode


Retourneert de geatomiseerde string die dezelfde tekens bevat als het gespecificeerde bereik van tekens in de gegeven array.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | De karakterarray die de te vinden naam bevat. |
| start | **int32_t** | De nulgebaseerde index in de array die het eerste teken van de naam aangeeft. |
| len | **int32_t** | Het aantal tekens in de naam. |

### Retourwaarde

De geatomiseerde string of **nullptr** als de string nog niet eerder is geatomiseerd. Als **len** nul is, wordt [String::Empty](../../../system/string/empty/) geretourneerd.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [NameTable](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)