---
title: SortedDictionary()
second_title: Aspose.Slides için C++ API Referansı
description: Boş bir sözlük oluşturur.
type: docs
weight: 14
url: /tr/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() yapıcı

Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) yapıcı

Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) kullanmak için. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Veri kopyalanacak kaynak sözlük. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Veri kopyalanacak kaynak sözlük. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) kullanmak için. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [SortedDictionary](../)
* Sınıf [IComparer](../../icomparer/)
* Sınıf [IDictionary](../../idictionary/)
* Ad alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)