---
title: Exchange()
second_title: Aspose.Slides voor C++ API-referentie
description: "Wisselt de waarde van een variabele: slaat de nieuwe waarde op en retourneert de waarde die de variabele had onmiddellijk vóór het opslaan."
type: docs
weight: 66
url: /nl/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) methode

Wisselt de waarde van een variabele: slaat de nieuwe waarde op en retourneert de waarde die de variabele had onmiddellijk vóór het opslaan.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Variable type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location1 | T\& | Variabelereferentie om te wijzigen. |
| value | T | Waarde om op te slaan. |

### Retourwaarde

Waarde van de variabele direct voordat deze werd gewijzigd.

## Interlocked::Exchange(T\&, T) methode

Wisselt de waarde van een variabele: slaat de nieuwe waarde op en retourneert de waarde die de variabele had onmiddellijk vóór het opslaan. Niet geïmplementeerd.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Variable type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location1 | T\& | Variabelereferentie om te wijzigen. |
| value | T | Waarde om op te slaan. |

### Retourwaarde

Waarde van de variabele direct voordat deze werd gewijzigd.

## Zie ook

* Klasse [Interlocked](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)