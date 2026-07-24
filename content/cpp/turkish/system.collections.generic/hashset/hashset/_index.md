---
title: HashSet()
second_title: Aspose.Slides for C++ API Referansı
description: RTTI bilgisi.
type: docs
weight: 1
url: /tr/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() yapıcı

RTTI bilgisi.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Açıklamalar

Boş küme oluşturur.

## HashSet::HashSet(int) yapıcı

Belirtilen kapasiteyle boş küme oluşturur.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) yapıcı

Belirtilen eşitlik karşılaştırıcısını kullanan boş küme oluşturur.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) hashset ile ilişkilendirilecek nesne. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) yapıcı

hashset, yinelenebilir değerlere göre oluşturulur.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [HashSet](../)
* Sınıf [IEqualityComparer](../../iequalitycomparer/)
* Sınıf [IEnumerable](../../ienumerable/)
* AdAlanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)