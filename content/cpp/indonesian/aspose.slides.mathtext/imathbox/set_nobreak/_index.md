---
title: set_NoBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "Tidak ada pemutusan. Properti ini menentukan properti \"unbreakable\" pada kotak objek. Ketika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true"
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metode

Tidak ada pemutusan. Properti ini menentukan properti \"unbreakable\" pada kotak objek. Ketika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Catatan

Contoh:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Lihat Juga

* Kelas [IMathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)