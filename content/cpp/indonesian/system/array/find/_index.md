---
title: Find()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari elemen pertama dalam array yang ditentukan yang memenuhi kondisi predikat yang diberikan.
type: docs
weight: 651
url: /id/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metode

Mencari elemen pertama dalam array yang ditentukan yang memenuhi kondisi predikat yang ditentukan.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) untuk mencari elemen dalam |
| match | [System::Predicate](../../predicate/)\<T\> | Predikat yang mendefinisikan kondisi untuk mencocokkan elemen array |

### Nilai Kembalian

Salinan elemen pertama dalam array yang memenuhi kondisi yang didefinisikan oleh predikat, jika tidak maka nilai default dari tipe T

## Lihat Juga

* Tipedef [ArrayPtr](../../arrayptr/)
* Tipedef [Predicate](../../predicate/)
* Kelas [Array](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)