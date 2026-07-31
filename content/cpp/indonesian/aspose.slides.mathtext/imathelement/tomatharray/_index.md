---
title: ToMathArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan dalam array vertikal
type: docs
weight: 183
url: /id/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metode


Menempatkan dalam array vertikal

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Nilai Kembalian

Instansi baru dari tipe [IMathArray](../../imatharray/)
## Catatan



Contoh: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathArray](../../imatharray/)
* Kelas [IMathElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)