---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, atomiseert de opgegeven tekenreeks en voegt deze toe aan de XmlNameTable.
type: docs
weight: 14
url: /nl/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) methode


Wanneer overschreven in een afgeleide klasse, atomiseert de opgegeven tekenreeks en voegt deze toe aan de [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | De tekenreeksarray die de toe te voegen naam bevat. |
| offset | **int32_t** | Nulgebaseerde index in de array die het eerste teken van de naam aangeeft. |
| length | **int32_t** | Het aantal tekens in de naam. |

### Retourwaarde

De nieuwe geatomiseerde tekenreeks of de bestaande als die al bestaat. Als de lengte nul is, wordt [String::Empty](../../../system/string/empty/) geretourneerd.

## XmlNameTable::Add(const String\&) methode


Wanneer overschreven in een afgeleide klasse, atomiseert de opgegeven tekenreeks en voegt deze toe aan de [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | De toe te voegen naam. |

### Retourwaarde

De nieuwe geatomiseerde tekenreeks of de bestaande als die al bestaat.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNameTable](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)