---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ Referensi API
description: "Pemecahan eksplisit menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris melipat pada awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan digunakan sebagai titik penyelarasan untuk baris saat ini dari teks matematis. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemecahan eksplisit)."
type: docs
weight: 118
url: /id/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metode

Pemecahan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek Box. Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan digunakan sebagai titik penyelarasan untuk baris saat ini dari teks matematis nilai yang mungkin: 1..255 Default: 0 (tidak ada pemecahan eksplisit)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Keterangan

Contoh:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lihat Juga

* Kelas [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)