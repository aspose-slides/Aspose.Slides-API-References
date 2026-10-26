---
title: IterateOver()
second_title: Aspose.Slides C++ API Referencia
description: "Ez a függvény tulajdonság becsomagolja az enumerálható (vagy iterálható) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusok nélkül, cél típus argumentummal a (auto& value : IterateOver<SomeType>(enumerable)) szintaxisra."
type: docs
weight: 2471
url: /hu/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusok nélkül, cél típus argumentummal a (auto& value : IterateOver<SomeType>(enumerable)) szintaxisra.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A cél típus, amelyet az iterátorból vissza kell adni |
| Enumerable | A becsomagolt objektum típusa |

## System::IterateOver(System::SmartPtr\<Enumerable\>) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára alapértelmezett cél típus argumentummal a (auto& value : IterateOver(enumerable)) szintaxisra, a következő C# kódnak megfelelően: foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Enumerable | A becsomagolt objektum típusa |

## System::IterateOver(System::SmartPtr\<Enumerable\>) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusokkal, alapértelmezett cél típus argumentummal a (auto& value : IterateOver(enumerable)) szintaxisra.

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Enumerable | A becsomagolt objektum típusa |

## System::IterateOver(System::SmartPtr\<Enumerable\>) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusokkal, a cél típus megegyezik az iterátor eredeti value_type értékével.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Enumerable | A becsomagolt objektum típusa |
| T | A cél típus, amelyet az iterátorból vissza kell adni |

## System::IterateOver(System::SmartPtr\<Enumerable\>) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusokkal, különböző cél típussal és az iterátor eredeti value_type értékével.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Enumerable | A becsomagolt objektum típusa |
| T | A cél típus, amelyet az iterátorból vissza kell adni |

## System::IterateOver(const Enumerable *) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára alapértelmezett cél típussal.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Enumerable | A becsomagolt objektum típusa |

## System::IterateOver(const Enumerable *) függvény


Ez a függvény tulajdonság becsomagolja az enumerable (vagy iterable) objektumot, hogy használható legyen tartományalapú for ciklussal. Ez a túlterhelés az Enumerable számára begin(), end() metódusok nélkül, cél típus argumentummal a (auto& value : IterateOver<SomeType>(enumerable)) szintaxisra.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A cél típus, amelyet az iterátorból vissza kell adni |
| Enumerable | A becsomagolt objektum típusa |

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [IsSmartPtr](../issmartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)