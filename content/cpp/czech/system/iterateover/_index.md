---
title: IterateOver()
second_title: Aspose.Slides pro C++ API Reference
description: "Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Toto přetížení pro Enumerable bez metod begin(), end() s argumentem cílového typu pro (auto& value : IterateOver<SomeType>(enumerable))."
type: docs
weight: 2471
url: /cs/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable bez metod begin(), end() s argumentem cílového typu pro (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ, který musí být vrácen z iterátoru |
| Enumerable | Typ zapouzdřeného objektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable bez metod begin(), end() s výchozím argumentem cílového typu pro (auto& value : IterateOver(enumerable)) analogicky k následujícímu kódu C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Enumerable | Typ zapouzdřeného objektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable s metodami begin(), end() s výchozím argumentem cílového typu pro (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Enumerable | Typ zapouzdřeného objektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable s metodami begin(), end() s cílovým typem stejným jako původní value_type iterátoru.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Enumerable | Typ zapouzdřeného objektu |
| T | Cílový typ, který musí být vrácen z iterátoru |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable s metodami begin(), end() s odlišným cílovým typem a původním value_type iterátoru.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Enumerable | Typ zapouzdřeného objektu |
| T | Cílový typ, který musí být vrácen z iterátoru |

## System::IterateOver(const Enumerable *) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable s výchozím cílovým typem.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Enumerable | Typ zapouzdřeného objektu |

## System::IterateOver(const Enumerable *) funkce


Tato funkční vlastnost zapouzdřuje objekt enumerable (nebo iterable), aby mohl být použit ve smyčce založené na rozsahu. Tato přetížení pro Enumerable bez metod begin(), end() s argumentem cílového typu pro (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ, který musí být vrácen z iterátoru |
| Enumerable | Typ zapouzdřeného objektu |

## Viz také

* Třída [SmartPtr](../smartptr/)
* Struktura [IsSmartPtr](../issmartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)