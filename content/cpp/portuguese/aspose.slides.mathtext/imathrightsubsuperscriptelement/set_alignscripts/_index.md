---
title: set_AlignScripts()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o alinhamento de subscrito/sobrescrito. Quando true, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando false, eles são ajustados ao formato da base. O valor padrão é false.
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) method

Especifica o alinhamento de subscrito/sobrescrito. Quando true, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando false, eles são ajustados ao formato da base. O valor padrão é false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## Observações

Exemplo:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Veja também

* Classe [IMathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)