---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar.
type: docs
weight: 209
url: /tr/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) yöntemi

Bir dizinin öğelerini, keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| keySelector | Bir öğeden anahtar çıkarmak için kullanılan işlev. |

### Dönüş Değeri

Anahtara göre sıralanmış öğeleri olan bir IOrderedEnumerable

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) yöntemi


```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Sınıf [Func](../../../system/func/)
* Sınıf [IEnumerable](../)
* AdAlanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)