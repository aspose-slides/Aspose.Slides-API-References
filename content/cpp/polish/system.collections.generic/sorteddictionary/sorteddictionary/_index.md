---
title: SortedDictionary()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy pusty słownik.
type: docs
weight: 14
url: /pl/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() konstruktor

Tworzy pusty słownik.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) konstruktor

Tworzy pusty słownik.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) do użycia. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Słownik źródłowy, z którego kopiowane są dane. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Słownik źródłowy, z którego kopiowane są dane. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) do użycia. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [SortedDictionary](../)
* Klasa [IComparer](../../icomparer/)
* Klasa [IDictionary](../../idictionary/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)