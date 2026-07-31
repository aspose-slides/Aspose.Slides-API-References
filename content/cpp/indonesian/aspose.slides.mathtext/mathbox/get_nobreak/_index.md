---
title: get_NoBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "No break Properti ini menentukan properti \"unbreakable\" pada kotak objek. Ketika true, tidak ada pemisahan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemisahan dapat terjadi di dalam kotak. Default: true"
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metode

No break Properti ini menentukan sifat "unbreakable" pada kotak objek. When true, tidak ada pemisahan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemisahan dapat terjadi di dalam kotak. Default: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Catatan

Contoh: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Lihat Juga

* Kelas [MathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)