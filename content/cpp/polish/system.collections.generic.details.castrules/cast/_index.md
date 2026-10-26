---
title: Cast()
second_title: Aspose.Slides dla C++ – referencja API
description: Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typy źródłowy i wynikowy są takie same.
type: docs
weight: 14
url: /pl/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typy źródłowy i wynikowy są takie same.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy może być statycznie rzutowany na typ wynikowy.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typy nie są takie same i typ źródłowy nie może być statycznie rzutowany na typ wynikowy.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest pakowany do instancji klasy [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest odpakowywany z instancji klasy [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest pakowany do instancji klasy [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest odpakowywany z instancji klasy [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## System::Collections::Generic::Details::CastRules::Cast(Source) funkcja


Rzutuje typ źródłowy na typ wynikowy. Używane, gdy rzutowanie jest nieprawidłowe lub konwersja jest jawna.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Wartość zwracana

Wynik rzutowania.

## Zobacz także

* Struktura [CastType](../casttype/)
* Przestrzeń nazw [System::Collections::Generic::Details::CastRules](../)
* Biblioteka [Aspose.Slides](../../)