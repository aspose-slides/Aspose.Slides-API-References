---
title: get_AlignScripts()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są kerowane do kształtu podstawy. Domyślna wartość to false.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metoda


Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są kerowane do kształtu podstawy. Domyślna wartość to false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Zobacz także

* Klasa [MathRightSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)