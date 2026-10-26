---
title: set_AlignScripts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan penyelarasan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka diperkirakan ke bentuk dasar. Nilai default adalah false.
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metode


Menentukan penyelarasan subskrip/superskrip. Ketika true, subskrip dan superskrip disejajarkan secara horizontal satu sama lain. Ketika false, mereka diperkirakan ke bentuk dasar. Nilai default adalah false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Keterangan


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