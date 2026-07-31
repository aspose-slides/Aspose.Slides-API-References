---
title: Exists()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah objek Array yang ditentukan berisi elemen yang memenuhi persyaratan predikat yang ditentukan.
type: docs
weight: 781
url: /id/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::.function\<bool(T)>) metode


Menentukan apakah objek [Array](../) yang ditentukan berisi elemen yang memenuhi persyaratan predikat yang ditentukan.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Array untuk mencari elemen di dalamnya |
| match | std::function\<**bool**(T)> | Objek fungsi yang mendefinisikan persyaratan dan memeriksa apakah elemen memenuhinya |

### Nilai Kembalian

True jika **arr** berisi elemen yang memenuhi persyaratan yang didefinisikan oleh **match**

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [Array](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)