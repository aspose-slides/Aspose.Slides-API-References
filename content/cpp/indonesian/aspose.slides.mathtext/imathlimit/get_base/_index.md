---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen dasar
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() metode


Argumen dasar

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
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
* Kelas [IMathLimit](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)