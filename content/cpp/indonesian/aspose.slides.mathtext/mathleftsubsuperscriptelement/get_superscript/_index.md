---
title: get_Superscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Superskrip
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() metode


Superskrip

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
```

## Catatan


Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathLeftSubSuperscriptElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)