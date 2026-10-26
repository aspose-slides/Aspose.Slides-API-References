---
title: Version
second_title: Aspose.Slides untuk Referensi API C++
description: "Mewakili nomor versi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 1470
url: /id/system/version/
---
## Version kelas

Mewakili nomor versi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../smartptr/) kelas untuk mengelola objek dari tipe ini.

```cpp
class Version
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Membandingkan versi yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Menentukan apakah nomor versi yang diwakili oleh objek saat ini dan objek yang ditentukan sama. |
| int [get_Build](./get_build/)() const | Mengembalikan nomor build. |
| int [get_Major](./get_major/)() const | Mengembalikan versi utama. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Mengembalikan nilai 16-bit tinggi dari nomor revisi. |
| int [get_Minor](./get_minor/)() const | Mengembalikan versi minor. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Mengembalikan nilai 16-bit rendah dari nomor revisi. |
| int [get_Revision](./get_revision/)() const | Mengembalikan nomor revisi. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Mengubah representasi string dari nomor versi menjadi instance yang setara dari [Version](./) kelas. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari nomor versi yang diwakili oleh objek saat ini. |
| [String](../string/) [ToString](./tostring/)(int) const | Mengembalikan representasi string dari jumlah bagian yang ditentukan dari nomor versi yang diwakili oleh objek saat ini. |
|  [Version](./version/)(int, int, int, int) | Membuat instance yang mewakili nilai mayor, minor, build, dan revisi yang ditentukan. |
|  [Version](./version/)(int, int, int) | Membuat instance yang mewakili nilai mayor, minor, dan build yang ditentukan. |
|  [Version](./version/)(int, int) | Membuat instance yang mewakili nilai mayor dan nilai yang ditentukan. |
|  [Version](./version/)(const [String](../string/)\&) | Membuat instance yang mewakili nomor versi yang direpresentasikan sebagai string. |
|  [Version](./version/)() | Membuat instance yang merepresentasikan nomor versi 0.0.-1.-1. |
## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)