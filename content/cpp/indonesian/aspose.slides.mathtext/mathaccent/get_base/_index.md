---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen yang diberikan aksen
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metode


Argumen yang diberikan aksen

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Keterangan


Contoh: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathAccent](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)