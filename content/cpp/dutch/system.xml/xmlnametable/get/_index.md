---
title: Get()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer deze in een afgeleide klasse wordt overschreven, haalt hij de geatomiseerde tekenreeks op die dezelfde tekens bevat als het opgegeven bereik van tekens in de gegeven array.
type: docs
weight: 1
url: /nl/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) methode


Wanneer deze in een afgeleide klasse wordt overschreven, haalt hij de geatomiseerde tekenreeks op die dezelfde tekens bevat als het opgegeven bereik van tekens in de gegeven array.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | De tekenreeksarray die de op te zoeken naam bevat. |
| offset | **int32_t** | De nulgebaseerde index in de array die het eerste teken van de naam aanduidt. |
| length | **int32_t** | Het aantal tekens in de naam. |

### Retourwaarde

De geatomiseerde tekenreeks of **nullptr** als de tekenreeks nog niet is geatomiseerd. Als **length** nul is, wordt [String::Empty](../../../system/string/empty/) geretourneerd.

## XmlNameTable::Get(const String\&) methode


Wanneer deze in een afgeleide klasse wordt overschreven, haalt hij de geatomiseerde tekenreeks op die dezelfde waarde heeft als de opgegeven tekenreeks.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | De op te zoeken naam. |

### Retourwaarde

De geatomiseerde tekenreeks of **nullptr** als de tekenreeks nog niet is geatomiseerd.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNameTable](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)