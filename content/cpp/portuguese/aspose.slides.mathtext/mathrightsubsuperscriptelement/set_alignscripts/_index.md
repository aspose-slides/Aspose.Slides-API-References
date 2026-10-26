---
title: set_AlignScripts()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica o alinhamento de subscrito/sobrescrito. Quando verdadeiro, subscrito e sobrescrito são alinhados horizontalmente um ao outro. Quando falso, são ajustados ao formato da base. O valor padrão é falso.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) método


Especifica o alinhamento de subscrito/sobrescrito. Quando verdadeiro, subscrito e sobrescrito são alinhados horizontalmente um ao outro. Quando falso, são ajustados ao formato da base. O valor padrão é falso.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

## Ver também

* Classe [MathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)