---
title: IterateOver()
second_title: Aspose.Slides für C++ API Referenz
description: "Diese Funktionseigenschaft kapselt ein enumerable (oder iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable ohne begin(), end() Methoden mit Zieltyp-Argument für (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /de/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (oder iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable ohne begin(), end()-Methoden mit Zieltyp-Argument für (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Zieltyp, er muss vom Iterator zurückgegeben werden |
| Enumerable | Der Typ eines gekapselten Objekts |

## System::IterateOver(System::SmartPtr\<Enumerable\>) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (or iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable ohne begin(), end()-Methoden mit Standard-Zieltyp-Argument für (auto& value : IterateOver(enumerable)) analog zum folgenden C#-Code foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Enumerable | Der Typ eines gekapselten Objekts |

## System::IterateOver(System::SmartPtr\<Enumerable\>) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (or iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable mit begin(), end()-Methoden mit Standard-Zieltyp-Argument für (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Enumerable | Der Typ eines gekapselten Objekts |

## System::IterateOver(System::SmartPtr\<Enumerable\>) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (or iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable mit begin(), end()-Methoden, bei der der Zieltyp dem ursprünglichen value_type des Iterators entspricht.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Enumerable | Der Typ eines gekapselten Objekts |
| T | Der Zieltyp, der vom Iterator zurückgegeben werden muss |

## System::IterateOver(System::SmartPtr\<Enumerable\>) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (or iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable mit begin(), end()-Methoden, bei der ein anderer Zieltyp als der ursprüngliche value_type des Iterators verwendet wird.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Enumerable | Der Typ eines gekapselten Objekts |
| T | Der Zieltyp, der vom Iterator zurückgegeben werden muss |

## System::IterateOver(const Enumerable *) Funktion


Diese Funktionseigenschaft kapselt ein enumerable (or iterable) Objekt, sodass es mit einer range-basierten for-Schleife verwendet werden kann. Diese Überladung für Enumerable mit Standard-Zieltyp.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Enumerable | Der Typ eines gekapselten Objekts |

## System::IterateOver(const Enumerable *) Funktion


Diese Überladung für Enumerable ohne begin(), end()-Methoden mit Zieltyp-Argument für (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Zieltyp, er muss vom Iterator zurückgegeben werden |
| Enumerable | Der Typ eines gekapselten Objekts |

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)