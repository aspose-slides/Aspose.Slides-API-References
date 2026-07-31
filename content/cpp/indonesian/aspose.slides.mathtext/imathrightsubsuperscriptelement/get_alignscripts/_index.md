---
title: get_AlignScripts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan penyelarasan subscript/superscript. Ketika true, subscript dan superscript diselaraskan secara horizontal satu sama lain. Ketika false, mereka dikernkan ke bentuk basis. Nilai default adalah false.
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() method

Menentukan penyelarasan subscript/superscript. Ketika true, subscript dan superscript disejajarkan secara horizontal satu sama lain. Ketika false, mereka dikernkan ke bentuk basis. Nilai default adalah false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

* Kelas [IMathRightSubSuperscriptElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)