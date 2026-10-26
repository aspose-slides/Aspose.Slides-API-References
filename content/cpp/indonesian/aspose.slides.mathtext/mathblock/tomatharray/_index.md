---
title: ToMathArray()
second_title: Aspose.Slides untuk Referensi API C++
description: Menempatkan elemen anak dalam array vertikal
type: docs
weight: 235
url: /id/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metode


Menempatkan elemen anak dalam array vertikal

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Nilai Kembali

Instansi baru dari tipe [IMathArray](../../imatharray/)
## Catatan



Contoh: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathArray](../../imatharray/)
* Kelas [MathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)