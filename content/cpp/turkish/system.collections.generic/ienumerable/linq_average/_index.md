---
title: LINQ_Average()
second_title: Aspose.Slides için C++ API Referansı
description: Sayısal değerlerden oluşan bir sekansın ortalamasını hesaplar.
type: docs
weight: 365
url: /tr/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() yöntemi


Sekans içindeki sayısal değerlerin ortalamasını hesaplar.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Dönüş Değeri

Sekanstaki değerlerin ortalaması.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) yöntemi


Girdi sekansının her öğesi üzerine bir dönüşüm işlevi çağrılarak elde edilen değerlerin ortalamasını hesaplar.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | Seçicinin döndürdüğü değerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Her öğeye uygulanacak dönüşüm işlevi. |

### Dönüş Değeri

Projeksiyon sonuçlarının ortalaması.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) yöntemi




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Ayrıca Bakınız

* Sınıf [IEnumerable](../)
* Sınıf [Func](../../../system/func/)
* Ad Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)