---
title: SmartPtrInfo
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas layanan untuk menguji dan mengubah isi SmartPtr tanpa mengetahui tipe akhir. Digunakan untuk pengumpulan sampah dan deteksi referensi siklus, dll. Anggap sebagai 'pointer to pointer'. Kami tidak dapat menggunakan tipe dasar SmartPtr karena tidak memiliki apa pun; sebagai gantinya, kami menggunakan kelas 'info' ini.
type: docs
weight: 1249
url: /id/system/smartptrinfo/
---
## SmartPtrInfo kelas

Kelas layanan untuk menguji dan mengubah isi [SmartPtr](../smartptr/) tanpa mengetahui tipe akhir. Digunakan untuk pengumpulan sampah dan deteksi referensi siklus, dll. Anggaplah ini sebagai 'pointer to pointer'. Kami tidak dapat menggunakan tipe dasar [SmartPtr](../smartptr/) karena tidak memiliki apa pun; sebagai gantinya, kami menggunakan kelas 'info' ini.

```cpp
class SmartPtrInfo
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Mendapatkan objek mentah yang ditunjuk oleh pointer referensi. |
| [Object](../object/) * [getObject](./getobject/)() const | Mendapatkan objek yang ditunjuk oleh pointer referensi. |
| [Object](../object/) * [getOwned](./getowned/)() const | Mendapatkan pointer yang dimiliki objek. |
|  [operator bool](./operator_bool/)() const | Memeriksa apakah objek info menunjuk ke pointer yang tidak null. |
| **bool** [operator!](./operator_not/)() const | Memeriksa apakah objek info tidak menunjuk ke pointer yang tidak null. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Memungkinkan memanggil metode [Object](../object/) yang ditunjuk oleh pointer referensi. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Membandingkan nilai pointer yang direferensikan oleh dua objek info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Membuat objek [SmartPtrInfo](./) kosong. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Membuat objek [SmartPtrInfo](./) dengan informasi tentang smart pointer tertentu. |

## Lihat Juga

* Ruang nama [System](../)
* Library [Aspose.Slides](../../)