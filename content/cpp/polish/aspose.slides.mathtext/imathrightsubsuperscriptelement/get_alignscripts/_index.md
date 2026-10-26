---
title: get_AlignScripts()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() metoda

Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## Zobacz też

* Klasa [IMathRightSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)