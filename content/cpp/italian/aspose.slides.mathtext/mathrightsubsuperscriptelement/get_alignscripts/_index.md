---
title: get_AlignScripts()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metodo


Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Osservazioni


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