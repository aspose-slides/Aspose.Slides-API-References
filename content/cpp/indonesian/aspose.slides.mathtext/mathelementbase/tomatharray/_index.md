---
title: ToMathArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan dalam array vertikal
type: docs
weight: 170
url: /id/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metode


Menempatkan dalam array vertikal

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
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
* Kelas [MathElementBase](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)