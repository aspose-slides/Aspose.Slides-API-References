---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: argumen Base
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metode

Base argumen

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Catatan

Contoh:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathRadical](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)