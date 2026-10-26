---
title: get_AlignScripts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan perataan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka dikernkan ke bentuk dasar. Nilai default adalah false.
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metode

Menentukan perataan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka dikernkan ke bentuk dasar. Nilai default adalah false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* Kelas [MathRightSubSuperscriptElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)