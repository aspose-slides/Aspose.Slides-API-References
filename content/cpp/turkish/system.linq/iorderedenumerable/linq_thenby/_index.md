---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizideki öğeleri anahtara göre artan sırada sonraki bir sıralama gerçekleştirir.
type: docs
weight: 27
url: /tr/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) metot

Bir dizideki öğeleri anahtara göre artan sırada sonraki bir sıralama gerçekleştirir.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Şablon Parametreleri

| Parametre | Açıklama |
| --- | --- |
| Key | keySelector tarafından döndürülen anahtarın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Her öğeden bir anahtar çıkarmak için bir işlev. |

### Dönüş Değeri

[System::Linq::IOrderedEnumerable](../) öğeleri bir anahtara göre sıralanmış.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) metot

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOrderedEnumerable](../)
* Sınıf [Func](../../../system/func/)
* Ad alanı [System::Linq](../../)
* Library [Aspose.Slides](../../../)