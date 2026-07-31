---
title: Build()
second_title: Aspose.Slides untuk Referensi API C++
description: Bangun sebuah objek dengan kepemilikan langsung.
type: docs
weight: 2289
url: /id/system/build/
---
## System::Build(Args&&...) fungsi

Bangun sebuah objek dengan kepemilikan langsung.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | Args&&... | Arguments to forward to object constructor |

### Nilai Kembalian

ObjectBuilder dikonfigurasi untuk konstruksi objek langsung

## Catatan

[Object](../object/) konstruksi harus diselesaikan dengan pemanggilan [Get()](../get/)

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)