---
title: set_AlignScripts()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metodo

Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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