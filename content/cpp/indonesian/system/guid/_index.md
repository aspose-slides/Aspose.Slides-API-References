---
title: Guid
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili Pengidentifikasi Global Unik. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 885
url: /id/system/guid/
---
## Guid kelas

Mewakili Pengidentifikasi Global Unik. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah gunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
class Guid
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Melakukan perbandingan aritmetika pada GUID yang direpresentasikan oleh objek saat ini dan objek yang ditentukan. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Menentukan apakah GUID yang direpresentasikan oleh objek saat ini dan objek yang ditentukan sama. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
|  [Guid](./guid/)() | Membuat objek yang merepresentasikan GUID yang terdiri dari semua nol. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Membuat objek yang merepresentasikan GUID yang ditentukan sebagai array nilai bilangan bulat tak bertanda 8-bit. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Membuat objek yang merepresentasikan GUID yang ditentukan sebagai tampilan array nilai bilangan bulat tak bertanda 8-bit. |
|  [Guid](./guid/)(const [String](../string/)\&) | Membuat objek yang merepresentasikan GUID yang ditentukan sebagai string. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Membuat instance kelas [Guid](./) dari komponen GUID yang ditentukan. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Membuat instance kelas [Guid](./) dari komponen GUID yang ditentukan. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Membuat instance kelas [Guid](./) dari bilangan bulat tak bertanda dan byte yang ditentukan. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Membuat instance kelas [Guid](./) dari bilangan bulat tak bertanda dan byte yang ditentukan. |
|  [Guid](./guid/)(const [Guid](./)\&) | Membuat objek yang merepresentasikan GUID yang sama dengan objek yang ditentukan. |
| static [Guid](./) [NewGuid](./newguid/)() | Menghasilkan GUID baru dan mengembalikan objek [Guid](./) yang merepresentasikannya. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Menentukan apakah GUID yang direpresentasikan oleh objek saat ini dan objek yang ditentukan tidak sama. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Menetapkan ke objek saat ini nilai GUID yang direpresentasikan oleh objek [Guid](./) yang ditentukan. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Menentukan apakah GUID yang direpresentasikan oleh objek saat ini dan objek yang ditentukan sama. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Mengonversi representasi string GUID yang ditentukan menjadi objek [Guid](./) yang setara. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Mengonversi GUID yang direpresentasikan oleh objek saat ini menjadi array byte. |
| [String](../string/) [ToString](./tostring/)() const | Mengonversi GUID yang direpresentasikan oleh objek saat ini ke representasi stringnya. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mengonversi GUID yang direpresentasikan oleh objek saat ini ke representasi stringnya menggunakan format string yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Mengonversi GUID yang direpresentasikan oleh objek saat ini ke representasi stringnya menggunakan format string dan Budaya yang ditentukan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Mencoba mengonversi string yang ditentukan menjadi objek [Guid](./). |
|  [~Guid](./~guid/)() | Destruktor. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Mewakili GUID yang memiliki nilai 0. |

## Lihat Juga

* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)