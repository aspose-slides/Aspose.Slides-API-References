---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizinin elemanlarını, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar.
type: docs
weight: 222
url: /tr/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) yöntemi

Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| keySelector | Bir öğeden anahtar çıkarmak için bir işlev. |

### Dönüş Değeri

Anahtarın azalan sırasına göre sıralanmış öğelere sahip bir IOrderedEnumerable

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) yöntemi

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Sınıf [Func](../../../system/func/)
* Sınıf [IEnumerable](../)
* İsim alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)