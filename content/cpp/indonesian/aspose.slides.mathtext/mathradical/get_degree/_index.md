---
title: get_Degree()
second_title: Referensi API Aspose.Slides untuk C++
description: Argument Derajat
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metode


Argument Derajat

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Catatan


Contoh: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Lihat Juga

* Tipe Definisi [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathRadical](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)