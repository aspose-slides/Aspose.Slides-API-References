---
title: IterateOver()
second_title: Aspose.Slides för C++ API-referens
description: "Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable utan begin(), end() metoder med måltypargument för (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /sv/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable utan begin(), end() metoder med måltypargument för (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Måltypen, den måste returneras från iterator |
| Enumerable | Typen av ett omslutet objekt |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable utan begin(), end() metoder med standardmåltypargument för (auto& value : IterateOver(enumerable)) analogt med följande C#-kod foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable med begin(), end() metoder med standardmåltypargument för (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable med begin(), end() metoder med måltyp samma som iteratorns ursprungliga value_type.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |
| T | Måltypen som måste returneras från iterator |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable med begin(), end() metoder med annan måltyp och iteratorns ursprungliga value_type.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |
| T | Måltypen som måste returneras från iterator |

## System::IterateOver(const Enumerable *) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable detta med standardmåltyp.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## System::IterateOver(const Enumerable *) funktion

Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range-baserad for-loop. Detta överlagring för Enumerable utan begin(), end() metoder med måltypargument för (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Måltypen, den måste returneras från iterator |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)