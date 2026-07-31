---
title: get_Limit()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen batas
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metode


Argument Batas

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Catatan


Contoh:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathLimit](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)