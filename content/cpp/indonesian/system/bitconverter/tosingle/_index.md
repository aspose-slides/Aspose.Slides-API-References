---
title: ToSingle()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan menjadi nilai floating-point presisi tunggal.
type: docs
weight: 131
url: /id/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metode


Mengonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan ke nilai floating-point presisi tunggal.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) yang berisi byte yang akan dikonversi |
| startIndex | int | [Index](../../index/) dalam array dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang dihasilkan dari konversi

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metode


Mengonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan ke nilai floating-point presisi tunggal.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView yang berisi byte yang akan dikonversi |
| startIndex | int | [Index](../../index/) dalam array dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang dihasilkan dari konversi

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)