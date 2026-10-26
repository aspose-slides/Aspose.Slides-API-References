---
title: get_Limit()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen batas
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() metode


Argumen batas

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
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
* Kelas [IMathLimit](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)