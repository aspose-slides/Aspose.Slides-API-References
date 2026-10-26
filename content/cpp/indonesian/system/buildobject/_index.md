---
title: BuildObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah objek dengan kepemilikan bersama.
type: docs
weight: 2250
url: /id/system/buildobject/
---
## System::BuildObject(Args\&&...) function

Membangun sebuah objek dengan kepemilikan bersama.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek yang akan dibangun |
| Args | Tipe argumen untuk konstruksi objek |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | Args\&&... | Argumen yang diteruskan ke konstruktor objek |

### Nilai Kembali

ObjectBuilder yang dikonfigurasi untuk konstruksi pointer bersama
## Catatan



Membuat SharedPtr<T> dan mengembalikan builder untuk itu 
[Object](../object/) konstruksi harus selesai dengan pemanggilan [Get()](../get/) 

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)