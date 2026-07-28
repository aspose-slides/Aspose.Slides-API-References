---
title: set_AlignScripts()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa wyrównanie indeksu dolnego i górnego. Gdy wartość jest true, indeks dolny i indeks górny są wyrównane poziomo względem siebie. Gdy wartość jest false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metoda

Określa wyrównanie indeksu dolnego/górnego. Gdy wartość jest true, indeks dolny i indeks górny są wyrównane poziomo względem siebie. Gdy wartość jest false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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