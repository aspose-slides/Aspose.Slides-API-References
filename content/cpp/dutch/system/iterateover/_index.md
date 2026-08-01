---
title: IterateOver()
second_title: Aspose.Slides voor C++ API Referentie
description: "Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable zonder begin(), end() methoden met target-type argument voor (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /nl/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable zonder begin(), end() methoden met target-type argument voor (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het target-type, het moet worden geretourneerd door de iterator |
| Enumerable | Het type van het gewikkelde object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable zonder begin(), end() methoden met standaard target-type argument voor (auto& value : IterateOver(enumerable)) analoog aan de volgende C#-code foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Enumerable | Het type van het gewikkelde object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable met begin(), end() methoden met standaard target-type argument voor (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Enumerable | Het type van het gewikkelde object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable met begin(), end() methoden met target-type gelijk aan de oorspronkelijke value_type van de iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Enumerable | Het type van het gewikkelde object |
| T | Het target-type dat door de iterator moet worden geretourneerd |

## System::IterateOver(System::SmartPtr\<Enumerable\>) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable met begin(), end() methoden met een ander target-type en de oorspronkelijke value_type van de iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Enumerable | Het type van het gewikkelde object |
| T | Het target-type dat door de iterator moet worden geretourneerd |

## System::IterateOver(const Enumerable *) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable met standaard target-type.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Enumerable | Het type van het gewikkelde object |

## System::IterateOver(const Enumerable *) functie


Deze functieweigenschap wikkelt een enumerable (of iterable) object zodat het kan worden gebruikt met een range-based for-lus. Deze overload voor Enumerable zonder begin(), end() methoden met target-type argument voor (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het target-type, het moet worden geretourneerd door de iterator |
| Enumerable | Het type van het gewikkelde object |

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Struct [IsSmartPtr](../issmartptr/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)