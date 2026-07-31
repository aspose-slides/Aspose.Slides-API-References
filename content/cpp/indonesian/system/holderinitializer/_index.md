---
title: HolderInitializer
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas ini digunakan untuk mendapatkan referensi persisten ke instance objek, baik itu lvalue maupun rvalue. Untuk memperoleh referensi tersebut, gunakan metode 'HoldIfTemporary' yang memiliki tiga overload. Dua di antaranya menerima rvalue sebagai parameter, dan hanya mengembalikan referensinya. Yang ketiga, sebaliknya, menerima lvalue sebagai parameter, membuat salinan pointer, kemudian mengembalikan referensi ke salinan tersebut. Selain itu, kelas memiliki metode 'Hold' untuk menahan nilai yang diberikan secara tak bersyarat (digunakan untuk menyalin nilai variabel lokal pada stack atau referensi anaknya).
type: docs
weight: 1639
url: /id/system/holderinitializer/
---
## HolderInitializer struct

Kelas ini digunakan untuk mendapatkan referensi persisten ke instance objek, baik itu lvalue maupun rvalue. Untuk memperoleh referensi tersebut, gunakan metode 'HoldIfTemporary' yang memiliki tiga overload. Dua di antaranya menerima rvalue sebagai parameter, dan hanya mengembalikan referensinya. Yang ketiga, sebaliknya, menerima lvalue sebagai parameter, membuat salinan pointer, lalu mengembalikan referensi ke salinan tersebut. Selain itu, kelas memiliki metode 'Hold' untuk menahan nilai yang diberikan tanpa kondisi (digunakan untuk menyalin nilai variabel lokal pada stack atau referensi anaknya).

```cpp
template<typename T,bool>class HolderInitializer
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek yang akan ditahan. |
| R | Benar, jika T adalah tipe referensi (spesialisasi [SmartPtr](../smartptr/) atau tipe [System::String](../string/)), dan penahanan referensi sementara memang diperlukan, salah - sebaliknya. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Menyalin lvalue yang diberikan ke holder, lalu mengembalikan referensi holder. Pemanggil harus menggunakan metode ini untuk menahan nilai yang diberikan tanpa kondisi. |
| [HolderInitializer](./holderinitializer/)(T\&) | Menginisialisasi referensi holder dengan nilai yang diberikan. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Mengembalikan referensi ke rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Mengembalikan referensi ke rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Menyalin lvalue yang diberikan ke holder, lalu mengembalikan referensi holder. |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)