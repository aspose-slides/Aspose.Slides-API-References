---
title: ToDouble()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi delapan byte dari array yang ditentukan mulai pada indeks yang ditentukan menjadi nilai floating-point presisi ganda.
type: docs
weight: 144
url: /id/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

Mengonversi delapan byte dari array yang ditentukan mulai pada indeks yang ditentukan menjadi nilai floating-point presisi ganda.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) di dalam array pada indeks dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai floating-point presisi ganda yang dihasilkan dari konversi

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

Mengonversi delapan byte dari array yang ditentukan mulai pada indeks yang ditentukan menjadi nilai floating-point presisi ganda.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) di dalam array pada indeks dimana mulai mengambil byte untuk konversi |

### Nilai Kembalian

Nilai floating-point presisi ganda yang dihasilkan dari konversi

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)