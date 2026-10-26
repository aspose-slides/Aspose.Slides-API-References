---
title: SortedDictionary()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein leeres Wörterbuch.
type: docs
weight: 14
url: /de/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() Konstruktor


Erzeugt ein leeres Wörterbuch.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) Konstruktor


Erzeugt ein leeres Wörterbuch.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) to use. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary to copy data from. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary to copy data from. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) to use. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SortedDictionary](../)
* Klasse [IComparer](../../icomparer/)
* Klasse [IDictionary](../../idictionary/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)