---
title: get_AlignScripts()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente l'uno con l'altro. Quando false, sono accoppiati alla forma della base. Il valore predefinito è false.
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() metodo


Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente l'uno con l'altro. Quando false, sono accoppiati alla forma della base. Il valore predefinito è false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

* Classe [IMathRightSubSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)