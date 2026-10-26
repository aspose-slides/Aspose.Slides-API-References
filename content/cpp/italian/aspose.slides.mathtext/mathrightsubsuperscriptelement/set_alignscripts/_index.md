---
title: set_AlignScripts()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono kerned alla forma della base. Il valore predefinito è false.
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metodo

Specifica l'allineamento di subscript/superscript. Quando true, subscript e superscript sono allineati orizzontalmente tra loro. Quando false, sono kerned alla forma della base. Il valore predefinito è false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Note

Esempio:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Vedi anche

* Classe [MathRightSubSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)