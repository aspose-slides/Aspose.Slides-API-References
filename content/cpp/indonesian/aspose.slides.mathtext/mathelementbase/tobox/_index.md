---
title: ToBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau contoh lain dari teks matematika. Sebuah objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya.
type: docs
weight: 261
url: /id/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metode

Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen persamaan atau teks matematis lainnya. Sebuah objek dalam kotak dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik putus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Nilai Kembali

Kotak logis dengan elemen ini ditempatkan di dalamnya

## Catatan

Contoh:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBox](../../imathbox/)
* Kelas [MathElementBase](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)