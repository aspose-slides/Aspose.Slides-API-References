---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen Fungsi
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metode

Argument Fungsi

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Keterangan

Contoh: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathFunction](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)