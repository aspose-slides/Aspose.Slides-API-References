---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen Base
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() metode

Argumen Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Catatan


Contoh:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathLimit](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)