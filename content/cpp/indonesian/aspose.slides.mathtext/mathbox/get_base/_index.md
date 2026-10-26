---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen Base
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metode


Argumen Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Catatan


Contoh: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)