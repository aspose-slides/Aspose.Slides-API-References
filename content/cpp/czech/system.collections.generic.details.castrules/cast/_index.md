---
title: Cast()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přetypuje zdrojový typ na typ výsledku. Používá se, když jsou zdrojový typ a typ výsledku stejné.
type: docs
weight: 14
url: /cs/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když jsou zdrojový typ a typ výsledku stejné.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když lze zdrojový typ staticky přetypovat na typ výsledku.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když typy nejsou stejné a zdrojový typ nelze staticky přetypovat na typ výsledku.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když je zdrojový typ zabalen do instance třídy [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když je zdrojový typ odbalen z instance třídy [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když je zdrojový typ zabalen do instance třídy [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když je zdrojový typ odbalen z instance třídy [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkce


Přetypuje zdrojový typ na typ výsledku. Používá se, když je přetypování neplatné nebo je konverze explicitní.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Typ výsledku. |

### Návratová hodnota

Výsledek přetypování.

## Viz také

* Struktura [CastType](../casttype/)
* Jmenný prostor [System::Collections::Generic::Details::CastRules](../)
* Knihovna [Aspose.Slides](../../)