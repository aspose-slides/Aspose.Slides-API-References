---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen Fungsi
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metode


Argumen Fungsi

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Catatan


Contoh: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathFunction](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)