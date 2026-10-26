---
title: FindIndex()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizide, belirtilen koşula uyan ilk öğeyi arar.
type: docs
weight: 638
url: /tr/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodu


Belirtilen dizide, belirtilen koşula uyan ilk öğeyi arar.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) içinde bir öğe aramak için |
| match | [System::Predicate](../../predicate/)\<T\> | Dizi öğelerini eşleştirmek için koşulları tanımlayan bir koşul |

### Dönüş Değeri

Koşul tarafından tanımlanan koşulları sağlayan dizideki ilk öğenin indeksi, aksi takdirde -1

## Diğer

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Sınıf [Array](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)