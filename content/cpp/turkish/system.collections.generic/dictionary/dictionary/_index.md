---
title: Dictionary()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir sözlük oluşturur.
type: docs
weight: 1
url: /tr/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() yapıcı

Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) yapıcı

Haritadan verileri kopyalar.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Kopyalanacak verilerin bulunduğu harita. |

## Dictionary::Dictionary(int) yapıcı

Önceden ayrılmış bir sözlük oluşturmayı karşılayan aşırı yük; aslında hiçbir tahsis yapmaz.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Kapasite tahsis etmek için; yok sayılır. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Verileri kopyalamak için [Dictionary](../). |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Kaynak sözlük. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Kullanılacak [Comparer](../../comparer/) nesnesi. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) yapıcı

Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Kullanılacak [Comparer](../../comparer/). |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) yapıcı

Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Oluşturma sonrası [Dictionary](../) kapasitesi; yok sayılır. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Kullanılacak [Comparer](../../comparer/). |

## Ayrıca Bakınız

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Dictionary](../)
* Sınıf [IDictionary](../../idictionary/)
* Sınıf [IEqualityComparer](../../iequalitycomparer/)
* AdAlanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)