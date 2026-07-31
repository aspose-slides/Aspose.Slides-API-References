---
title: InitObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai inisialisasi objek dengan kepemilikan bersama.
type: docs
weight: 2263
url: /id/system/initobject/
---
## System::InitObject(const SharedPtr<T>&) fungsi

Memulai inisialisasi objek dengan kepemilikan bersama.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek yang akan diinisialisasi |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)<T>& | [Object](../object/) untuk diinisialisasi |

### Nilai kembali

ObjectBuilder yang dikonfigurasi untuk konstruksi shared pointer

## Catatan

[Object](../object/) inisialisasi harus diselesaikan dengan pemanggilan [Get()](../get/) 

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)