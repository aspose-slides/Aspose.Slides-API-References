---
title: Sign()
second_title: Aspose.Slides for C++ API Referentie
description: Bepaalt het teken van de opgegeven ondertekende gehele waarde.
type: docs
weight: 274
url: /nl/system/mathf/sign/
---
## MathF::Sign(T) methode


Bepaalt het teken van de opgegeven ondertekende gehele waarde.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het ondertekende gehele type |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde waarvan het teken moet worden bepaald |

### Retourwaarde

- 1 als **value** kleiner is dan 0; 0 als **value** gelijk is aan 0; 1 als **value** groter is dan 0

## MathF::Sign(T) methode


Bepaalt het teken van de opgegeven zwevend-komma waarde.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het zwevend-komma type van het argument |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde waarvan het teken moet worden bepaald |

### Retourwaarde

- 1 als **value** kleiner is dan 0; 0 als **value** gelijk is aan 0; 1 als **value** groter is dan 0

## Zie ook

* Struct [MathF](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)