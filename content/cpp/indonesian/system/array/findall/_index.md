---
title: FindAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil semua elemen yang cocok dengan kondisi yang didefinisikan oleh predikat yang ditentukan.
type: docs
weight: 664
url: /id/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metode

Mengambil semua elemen yang memenuhi kondisi yang didefinisikan oleh predikat yang ditentukan.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) untuk mencari elemen dalam |
| match | [System::Predicate](../../predicate/)\<T\> | Sebuah predikat yang mendefinisikan kondisi untuk mencocokkan elemen array |

### Nilai Kembalian

Sebuah [Array](../) yang berisi semua elemen yang cocok dengan kondisi yang didefinisikan oleh predikat yang ditentukan, jika ditemukan; jika tidak, sebuah [Array](../) kosong.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)