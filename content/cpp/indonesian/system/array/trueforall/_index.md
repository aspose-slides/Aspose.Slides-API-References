---
title: TrueForAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah semua elemen dalam array yang ditentukan memenuhi kondisi yang didefinisikan oleh predikat yang diberikan.
type: docs
weight: 677
url: /id/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metode

Menentukan apakah semua elemen dalam array yang ditentukan memenuhi kondisi yang didefinisikan oleh predikat yang diberikan.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elemen yang akan dicocokkan dengan kondisi |
| match | [System::Predicate](../../predicate/)\<T\> | Predikat yang mendefinisikan kondisi untuk mencocokkan elemen array |

### Nilai Kembalian

true jika semua elemen array arr memenuhi kondisi yang didefinisikan oleh predikat match, jika tidak false

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Kelas [Array](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)