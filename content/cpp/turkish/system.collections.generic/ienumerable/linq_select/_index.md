---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizinin öğelerini dönüştürür.
type: docs
weight: 248
url: /tr/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metot

Bir dizinin öğelerini dönüştürür.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | **selector** tarafından döndürülen değerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Bir dönüştürme işlevi. |

### Dönüş Değeri

**selector** işlevi tarafından döndürülen öğeleri içeren bir [IEnumerable](../).

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metot

Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir biçime dönüştürür.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ResultType | **selector** tarafından döndürülen değerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Bir dönüştürme işlevi. |

### Dönüş Değeri

**selector** işlevi tarafından döndürülen öğeleri içeren bir [IEnumerable](../).

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metot

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metot

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Diğer Bağlantılar

* Tip Tanımlayıcı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IEnumerable](../)
* Sınıf [Func](../../../system/func/)
* Ad alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)