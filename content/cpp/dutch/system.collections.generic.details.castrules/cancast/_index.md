---
title: CanCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert de mogelijkheid om te casten.
type: docs
weight: 40
url: /nl/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

True wanneer een niet nullptr waarde wordt geretourneerd na het casten, anders false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

True wanneer een niet nullptr waarde wordt geretourneerd na het casten, anders false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

True wanneer een niet nullptr waarde wordt geretourneerd na het casten, anders false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

Altijd true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

True wanneer een niet nullptr waarde wordt geretourneerd na het casten, anders false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

Altijd true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

True indien de castbewerking succesvol was uitgevoerd, anders false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) functie


Controleert de mogelijkheid om te casten.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het bron type. |
| Result | Het resultaat type. |

### Retourwaarde

Altijd false.

## Zie ook

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Bibliotheek [Aspose.Slides](../../)