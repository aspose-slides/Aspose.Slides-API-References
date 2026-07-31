---
title: CharacterRange
second_title: Referensi API Aspose.Slides untuk C++
description: "Merepresentasikan rentang posisi karakter dalam sebuah string. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 40
url: /id/system.drawing/characterrange/
---
## CharacterRange kelas

Merepresentasikan rentang posisi karakter dalam sebuah string. Tipe ini seharusnya dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah gunakan kelas [System::SmartPtr](../../system/smartptr/) untuk mengelola objek dari tipe ini.

```cpp
class CharacterRange
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Membuat instance baru dari kelas [CharacterRange](./) yang merepresentasikan rentang yang ditentukan. |
|  [CharacterRange](./characterrange/)() | Membuat instance baru dari kelas [CharacterRange](./) yang merepresentasikan rentang kosong. |
| **int32_t** [get_First](./get_first/)() const | Mengembalikan posisi karakter pertama dari rentang yang direpresentasikan oleh objek saat ini. |
| **int32_t** [get_Length](./get_length/)() const | Mengembalikan jumlah karakter dalam rentang yang direpresentasikan oleh objek saat ini. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan merepresentasikan rentang yang berbeda. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan merepresentasikan rentang yang sama. |
| void [set_First](./set_first/)(**int32_t**) | Mengatur posisi karakter pertama dari rentang yang direpresentasikan oleh objek saat ini. |
| void [set_Length](./set_length/)(**int32_t**) | Mengembalikan jumlah karakter dalam rentang yang direpresentasikan oleh objek saat ini. |

## Lihat Juga

* ruang nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)