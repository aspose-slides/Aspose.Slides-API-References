---
title: CompareExchange()
second_title: Aspose.Slides voor C++ API-referentie
description: "Vergelijkt en wisselt de waarde van een variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte."
type: docs
weight: 79
url: /nl/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) methode

Vergelijkt en wisselt de waarde van een variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Variabeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location1 | T\& | Variabelereferentie die moet worden gewijzigd. |
| value | T | Te bewaren waarde. |
| comparand | T | Waarde waarmee de variabelewaarde wordt vergeleken vóór het uitwisselen. |

### Retourwaarde

Waarde van de variabele bij het begin van de operatie, ongeacht of deze is gewijzigd of niet.

## Interlocked::CompareExchange(T\&, T, T) methode

Vergelijkt en wisselt de waarde van een variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte. Niet geïmplementeerd.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Variabeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location1 | T\& | Variabelereferentie die moet worden gewijzigd. |
| value | T | Te bewaren waarde. |
| comparand | T | Waarde waarmee de variabelewaarde wordt vergeleken vóór het uitwisselen. |

### Retourwaarde

Waarde van de variabele bij het begin van de operatie, ongeacht of deze is gewijzigd of niet.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) methode

Vergelijkt en wisselt de waarde van een variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location1 | **int32_t**\& | Variabelereferentie die moet worden gewijzigd. |
| value | **int32_t** | Te bewaren waarde. |
| comparand | **int32_t** | Waarde waarmee de variabelewaarde wordt vergeleken vóór het uitwisselen. |
| succeeded | **bool**\& | Referentie naar een variabele die op true wordt gezet als de uitwisseling heeft plaatsgevonden en anders op false. |

### Retourwaarde

Waarde van de variabele bij het begin van de operatie, ongeacht of deze is gewijzigd of niet.

## Zie ook

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)