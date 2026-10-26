---
title: ToUInt64()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi delapan byte dari array yang ditentukan mulai dari indeks yang ditentukan menjadi nilai bilangan bulat tak bertanda 64-bit.
type: docs
weight: 118
url: /id/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metode

Mengonversi delapan byte dari array yang ditentukan mulai dari indeks yang ditentukan menjadi nilai bilangan bulat tak bertanda 64-bit.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) di dalam array pada posisi dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai bilangan bulat tak bertanda 64-bit yang dihasilkan dari konversi

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metode

Mengonversi delapan byte dari array yang ditentukan mulai dari indeks yang ditentukan menjadi nilai bilangan bulat tak bertanda 64-bit.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) di dalam array pada posisi dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai bilangan bulat tak bertanda 64-bit yang dihasilkan dari konversi

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [BitConverter](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)