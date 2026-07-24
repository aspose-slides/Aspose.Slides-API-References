---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API Referansı
description: Genel bir dizideki her öğeye bir dönüştürme işlevi uygular ve ortaya çıkan en büyük değeri döndürür.
type: docs
weight: 352
url: /tr/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metod


Genel bir dizideki her öğeye bir dönüştürme işlevi uygular ve ortaya çıkan en büyük değeri döndürür.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | Seçici tarafından döndürülen değerin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Her öğeye uygulanacak bir dönüştürme işlevi. |

### Dönüş Değeri

Dizideki en büyük değer.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metod




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Ayrıca Bakınız

* Sınıf [Func](../../../system/func/)
* Sınıf [IEnumerable](../)
* Ad alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)