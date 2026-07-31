---
title: Dictionary()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat kamus kosong.
type: docs
weight: 1
url: /id/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() konstruktor


Membuat kamus kosong.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) konstruktor


Menyalin data dari peta.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Peta untuk menyalin data dari. |

## Dictionary::Dictionary(int) konstruktor


Overload yang sesuai dengan pembuatan kamus berkapasitas tetap; tidak melakukan alokasi, sebenarnya.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| capacity | int | Kapasitas untuk dialokasikan; diabaikan. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor


Konstruktor salin.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) untuk menyalin data dari. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Konstruktor salin.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Kamus sumber. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objek yang akan digunakan. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Membuat kamus kosong.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) untuk digunakan. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor


Membuat kamus kosong.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| capacity | int | [Dictionary](../) kapasitas setelah pembuatan; diabaikan. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) untuk digunakan. |

## Lihat Juga

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)