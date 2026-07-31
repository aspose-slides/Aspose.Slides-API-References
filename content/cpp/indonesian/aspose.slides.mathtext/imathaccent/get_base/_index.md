---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen yang diterapkan aksen
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metode


Argumen yang diterapkan aksen

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Catatan


Contoh: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathAccent](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)