---
title: CanCast()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Kontroluje možnost přetypování.
type: docs
weight: 40
url: /cs/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vrací true, pokud po přetypování hodnota není nullptr, jinak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vrací true, pokud po přetypování hodnota není nullptr, jinak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vrací true, pokud po přetypování hodnota není nullptr, jinak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vždy vrací true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vrací true, pokud po přetypování hodnota není nullptr, jinak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vždy vrací true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vrací true, pokud byla operace přetypování úspěšně provedena, jinak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkce


Kontroluje možnost přetypování.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Typ zdroje. |
| Result | Typ výsledku. |

### Návratová hodnota

Vždy vrací false.

## Viz také

* Struktura [CastType](../casttype/)
* Jmenný prostor [System::Collections::Generic::Details::CastRules](../)
* Knihovna [Aspose.Slides](../../)