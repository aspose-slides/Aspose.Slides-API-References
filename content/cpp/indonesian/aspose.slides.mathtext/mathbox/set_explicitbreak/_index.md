---
title: set_ExplicitBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris melipat di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik perataan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit)"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) method


Explicit break menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris melipat di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik perataan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (no explicit break)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Catatan


Contoh: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lihat Juga

* Kelas [MathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)