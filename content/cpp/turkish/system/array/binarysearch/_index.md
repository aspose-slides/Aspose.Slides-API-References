---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Referansı
description: Sıralı dizide ikili arama gerçekleştirir.
type: docs
weight: 612
url: /tr/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method

Sıralı dizide ikili arama gerçekleştirir.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Aramanın gerçekleştirileceği sıralı dizi |
| item | const T\& | Aranacak öğe |

### Dönüş Değeri

[Index](../../index/) aranan öğenin; eğer bulunursa, aksi takdirde aranan öğeden daha büyük bir sonraki öğenin indeksinin bitwise tamamlayıcısı olan negatif bir tam sayı veya daha büyük bir öğe yoksa dizideki eleman sayısının bitwise tamamlayıcısı.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method

UYGULANMADI.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)