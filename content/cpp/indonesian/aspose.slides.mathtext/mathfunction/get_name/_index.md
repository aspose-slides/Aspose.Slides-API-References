---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Nama fungsi. Misalnya, nama fungsi adalah sin dan cos
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metode


Nama fungsi Misalnya, nama fungsi adalah sin dan cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Keterangan


Contoh: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathFunction](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)