---
title: IterateOver()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu może być używany w pętli opartej na zakresach. Ten overload dla Enumerable bez metod begin(), end() z argumentem typu docelowego dla (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /pl/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable bez metod begin(), end() z argumentem typu docelowego dla (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy, który musi być zwracany z iteratora |
| Enumerable | Typ opakowanego obiektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable bez metod begin(), end() z domyślnym argumentem typu docelowego dla (auto& value : IterateOver(enumerable)) analogicznie do poniższego kodu C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Enumerable | Typ opakowanego obiektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable z metodami begin(), end() z domyślnym argumentem typu docelowego dla (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Enumerable | Typ opakowanego obiektu |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable z metodami begin(), end() z typem docelowym takim samym jak oryginalny value_type iteratora.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Enumerable | Typ opakowanego obiektu |
| T | Typ docelowy, który musi być zwracany z iteratora |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable z metodami begin(), end() z innym typem docelowym niż oryginalny value_type iteratora.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Enumerable | Typ opakowanego obiektu |
| T | Typ docelowy, który musi być zwracany z iteratora |

## System::IterateOver(const Enumerable *) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable z domyślnym typem docelowym.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Enumerable | Typ opakowanego obiektu |

## System::IterateOver(const Enumerable *) funkcja

Ta właściwość funkcji opakowuje obiekt enumerable (lub iterable), dzięki czemu można go używać w pętli opartej na zakresach. Ten overload dla Enumerable bez metod begin(), end() z argumentem typu docelowego dla (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy, który musi być zwracany z iteratora |
| Enumerable | Typ opakowanego obiektu |

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [IsSmartPtr](../issmartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)