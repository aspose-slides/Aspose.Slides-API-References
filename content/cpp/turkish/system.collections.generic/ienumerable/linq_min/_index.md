---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API Referansı
description: Genel bir dizideki her öğeye bir dönüşüm işlevi uygular ve elde edilen minimum değeri döndürür.
type: docs
weight: 339
url: /tr/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metodu

Genel bir dizi içindeki her öğeye bir dönüşüm işlevi uygular ve elde edilen minimum değeri döndürür.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | Seçicinin döndürdüğü değerin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Her öğeye uygulanacak bir dönüşüm işlevi. |

### Dönüş Değeri

Dizideki minimum değer.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metodu




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Ayrıca Bakınız

* Sınıf [Func](../../../system/func/)
* Sınıf [IEnumerable](../)
* Ad Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)