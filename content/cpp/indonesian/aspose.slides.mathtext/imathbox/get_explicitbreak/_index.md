---
title: get_ExplicitBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "Explicit break menentukan apakah ada jeda baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan digunakan sebagai titik perataan untuk baris teks matematis saat ini. Nilai yang memungkinkan: 1..255 Default: 0 (tidak ada explicit break)"
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metode

Explicit break menentukan apakah ada jeda baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematis yang akan digunakan sebagai titik perataan untuk baris teks matematis saat ini. Nilai yang memungkinkan: 1..255 Default: 0 (tidak ada explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
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
* Pustaka [Aspose.Slides](../../../)