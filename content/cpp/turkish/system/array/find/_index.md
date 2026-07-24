---
title: Find()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizide, belirtilen koşulun şartlarını karşılayan ilk öğeyi arar.
type: docs
weight: 651
url: /tr/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) yöntemi

Belirtilen dizide, belirtilen koşulları sağlayan ilk öğeyi arar.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) içinde bir öğeyi aramak için |
| match | [System::Predicate](../../predicate/)\<T\> | Dizi elemanlarını eşleştirmek için koşulları tanımlayan bir koşul |

### Dönüş Değeri

Koşul tarafından tanımlanan koşulları karşılayan dizideki ilk elemanın kopyası; aksi takdirde T tipinin varsayılan değeri

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Sınıf [Array](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)