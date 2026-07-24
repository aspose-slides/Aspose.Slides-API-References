---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizinin her öğesini projeler ve ortaya çıkan dizileri tek bir diziye birleştirir.
type: docs
weight: 300
url: /tr/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Bir dizinin her öğesini projeler ve ortaya çıkan dizileri tek bir diziye birleştirir.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | **selector** tarafından döndürülen değerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Bir dönüşüm işlevi. |

### Dönüş Değeri

Girdi dizisinin her öğesine bir-çok projeksiyon işlevi uygulamanın sonucunu içeren bir [IEnumerable](../).

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)