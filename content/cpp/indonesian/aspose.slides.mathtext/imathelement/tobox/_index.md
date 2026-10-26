---
title: ToBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen sebuah persamaan atau contoh teks matematika lainnya. Sebuah objek yang dikotakkan dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya.
type: docs
weight: 274
url: /id/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metode


Menempatkan elemen ini dalam kotak non-visual (pengelompokan logis) yang digunakan untuk mengelompokkan komponen sebuah persamaan atau contoh teks matematika lainnya. Sebuah objek yang dikotakkan dapat (misalnya) berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### Nilai Kembali

Kotak logis dengan elemen ini ditempatkan di dalamnya
## Keterangan



Contoh: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBox](../../imathbox/)
* Kelas [IMathElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)