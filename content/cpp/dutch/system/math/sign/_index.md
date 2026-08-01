---
title: Sign()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het teken van de opgegeven ondertekende integrale waarde.
type: docs
weight: 274
url: /nl/system/math/sign/
---
## Math::Sign(T) methode


Bepaalt het teken van de opgegeven ondertekende gehele waarde.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het ondertekende integrale type |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde waarvan het teken moet worden bepaald |

### Retourwaarde

- 1 als **value** kleiner is dan 0; 0 als **value** gelijk is aan 0; 1 als **value** groter is dan 0

## Math::Sign(T) methode


Bepaalt het teken van de opgegeven zwevend-kommagetalwaarde.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het zwevend-kommagetype van het argument |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde waarvan het teken moet worden bepaald |

### Retourwaarde

- 1 als **value** kleiner is dan 0; 0 als **value** gelijk is aan 0; 1 als **value** groter is dan 0

## Math::Sign(const Decimal\&) methode


Bepaalt het teken van de opgegeven decimale waarde.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | De waarde waarvan het teken moet worden bepaald |

### Retourwaarde

- 1 als **value** kleiner is dan 0; 0 als **value** gelijk is aan 0; 1 als **value** groter is dan 0

## Zie ook

* Klasse [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)