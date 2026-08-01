---
title: IndexOfAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Voorwaartse opzoeking van teken.
type: docs
weight: 638
url: /nl/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const methode


Voorwaartse opzoeking van teken.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | char_t | Teken om naar te zoeken. |
| startIndex | int | [Index](../../index/) om de zoekopdracht te starten bij. |

### Retourwaarde

[Index](../../index/) van de eerste tekenpositie sinds startIndex of -1 indien niet gevonden.

## String::IndexOfAny(const String\&, int) const methode


Zoekt vervolgens naar alle tekens van str in dit. Als het eerste teken wordt gevonden, wordt de positie geretourneerd, anders wordt naar het tweede gezocht enzovoort.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) van tekens om naar te zoeken. Volgorde van tekens is belangrijk. |
| startIndex | int | Positie om de zoekopdracht te starten vanaf. |

### Retourwaarde

[Index](../../index/) van het eerst gevonden teken of -1 indien geen gevonden.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const methode


Zoekt naar elk van de meegegeven tekens in de hele tekenreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, vervolgens het tweede enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van tekens om naar te zoeken. Volgorde is niet van belang. |

### Retourwaarde

[Index](../../index/) van het eerste overeenkomende teken of -1 indien niet gevonden.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const methode


Zoekt naar elk van de meegegeven tekens in een subreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, vervolgens het tweede enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van tekens om naar te zoeken. Volgorde is niet van belang. |
| startindex | **int32_t** | [Index](../../index/) om de zoekopdracht te starten vanaf. |

### Retourwaarde

[Index](../../index/) van het eerste overeenkomende teken of -1 indien niet gevonden.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const methode


Zoekt naar elk van de meegegeven tekens in een subreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, vervolgens het tweede enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van tekens om naar te zoeken. Volgorde is niet van belang. |
| startindex | **int32_t** | [Index](../../index/) om de zoekopdracht te starten vanaf. |
| count | **int32_t** | Aantal tekens om doorheen te zoeken. |

### Retourwaarde

[Index](../../index/) van het eerste overeenkomende teken of -1 indien niet gevonden.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)