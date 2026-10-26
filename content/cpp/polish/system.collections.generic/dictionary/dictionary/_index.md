---
title: Dictionary()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy pusty słownik.
type: docs
weight: 1
url: /pl/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() konstruktor


Tworzy pusty słownik.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) konstruktor


Kopiuje dane z mapy.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa, z której kopiowane są dane. |

## Dictionary::Dictionary(int) konstruktor


Przeciążenie odpowiadające tworzeniu wstępnie przydzielonego słownika; w rzeczywistości nie dokonuje alokacji.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| capacity | int | Pojemność do alokacji; ignorowana. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor


Konstruktor kopiujący.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) do skopiowania danych z. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Konstruktor kopiujący.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Źródłowy słownik. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) obiekt do użycia. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Tworzy pusty słownik.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) do użycia. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Tworzy pusty słownik.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| capacity | int | [Dictionary](../) pojemność po utworzeniu; ignorowana. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) do użycia. |

## Zobacz także

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Dictionary](../)
* Klasa [IDictionary](../../idictionary/)
* Klasa [IEqualityComparer](../../iequalitycomparer/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)