---
title: set_AlignScripts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan perataan subscript/superscript. Ketika true, subscript dan superscript disejajarkan secara horizontal satu sama lain. Ketika false, mereka kerned ke bentuk dasar. Nilai default adalah false.
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metode

Menentukan perataan subscript/superscript. Ketika true, subscript dan superscript disejajarkan secara horizontal satu sama lain. Ketika false, mereka kerned ke bentuk dasar. Nilai default adalah false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Lihat Juga

* Kelas [IMathRightSubSuperscriptElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)