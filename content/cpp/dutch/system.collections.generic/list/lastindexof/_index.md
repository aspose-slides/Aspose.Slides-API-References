---
title: LastIndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen de volledige lijst.
type: docs
weight: 469
url: /nl/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const methode

Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen de volledige lijst.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Het object om in de lijst te vinden |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen van item binnen de volledige [List](../), indien gevonden; anders -1.

## List::LastIndexOf(const T\&, int32_t) const methode

Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen het bereik van elementen in de [List](../) dat zich uitstrekt van het eerste element tot de opgegeven index.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Het object om in de lijst te vinden |
| index | **int32_t** | De nulgebaseerde startindex van de achterwaartse zoekopdracht. |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen van item binnen het bereik van elementen in de [List](../) dat zich uitstrekt van het eerste element tot index, indien gevonden; anders -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const methode

Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen het bereik van elementen in de [List](../) dat het opgegeven aantal elementen bevat en eindigt op de opgegeven index.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Het object om in de [List](../) te vinden |
| index | **int32_t** | De nulgebaseerde startindex van de achterwaartse zoekopdracht. |
| count | **int32_t** | Het aantal elementen in de te doorzoeken sectie. |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen van item binnen het bereik van elementen in de [List](../) dat count aantal elementen bevat en eindigt op index, indien gevonden; anders -1.

## Zie ook

* Klasse [List](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)