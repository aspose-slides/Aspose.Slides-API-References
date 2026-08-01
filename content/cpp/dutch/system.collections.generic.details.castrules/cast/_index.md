---
title: Cast()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert het brontype naar het resultaattype. Wordt gebruikt wanneer het bron- en resultaattype gelijk zijn.
type: docs
weight: 14
url: /nl/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het bron- en resultaattype gelijk zijn.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het brontype statisch kan worden geconverteerd naar het resultaattype.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer de typen niet hetzelfde zijn en het brontype niet statisch kan worden geconverteerd naar het resultaattype.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het brontype wordt geboxed naar de [Nullable](../../system/nullable/) klasse-instantie.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het brontype wordt gedeboxed van de [Nullable](../../system/nullable/) klasse-instantie.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het brontype wordt geboxed naar de [Object](../../system/object/) klasse-instantie.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer het brontype wordt gedeboxed van de [Object](../../system/object/) klasse-instantie.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## System::Collections::Generic::Details::CastRules::Cast(Source) functie


Converteert het brontype naar het resultaattype. Gebruikt wanneer de cast ongeldig is of de conversie expliciet is.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resultaattype. |

### Retourwaarde

Het cast-resultaat.

## Zie ook

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)