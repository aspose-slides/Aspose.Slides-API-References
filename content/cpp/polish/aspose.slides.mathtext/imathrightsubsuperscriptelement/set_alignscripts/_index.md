---
title: set_AlignScripts()
second_title: Aspose.Slides dla C++ odniesienie API
description: Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metoda


Określa wyrównanie indeksu dolnego/górnego. Gdy true, indeks dolny i górny są wyrównane poziomo względem siebie. Gdy false, są dopasowywane do kształtu podstawy. Domyślna wartość to false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* Klasa [IMathRightSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)