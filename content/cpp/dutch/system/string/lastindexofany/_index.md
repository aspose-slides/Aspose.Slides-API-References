---
title: LastIndexOfAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar een van de meegegeven tekens in de hele tekenreeks, achterwaarts. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, vervolgens het vorige teken enzovoort. Retourneert de index van de eerste gevonden overeenkomst.
type: docs
weight: 664
url: /nl/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

Zoekt naar een van de meegegeven tekens in de hele tekenreeks, terugwerkend. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, vervolgens het vorige teken enzovoort. Retourneert de index van de eerste gevonden overeenkomst.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |

### Retourwaarde

[Index](../../index/) van het laatste overeenkomende teken of -1 indien niet gevonden.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

Zoekt naar een van de meegegeven tekens in een subreeks, terugwerkend. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, vervolgens het vorige teken enzovoort. Retourneert de index van de eerste gevonden overeenkomst.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | [Index](../../index/) om van te beginnen zoeken. |

### Retourwaarde

[Index](../../index/) van het laatste overeenkomende teken of -1 indien niet gevonden.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

Zoekt naar een van de meegegeven tekens in een subreeks, terugwerkend. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, vervolgens het vorige teken enzovoort. Retourneert de index van de eerste gevonden overeenkomst.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | [Index](../../index/) om van te beginnen zoeken. |
| count | **int32_t** | Aantal tekens om door te zoeken. |

### Retourwaarde

[Index](../../index/) van het laatste overeenkomende teken of -1 indien niet gevonden.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)