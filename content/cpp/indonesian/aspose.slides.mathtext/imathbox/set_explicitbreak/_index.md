---
title: set_ExplicitBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "Explicit break menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit)"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metode

Explicit break menentukan apakah terdapat pemutusan baris di awal objek Box, sehingga baris membungkus pada awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## Catatan


Contoh: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lihat Juga

* Kelas [IMathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)