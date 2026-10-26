---
title: get_AlignScripts()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o alinhamento de subscrito/sobrescrito. Quando true, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando false, são ajustados à forma da base. O valor padrão é false.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() método


Especifica o alinhamento de subscrito/sobrescrito. Quando true, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando false, são ajustados à forma da base. O valor padrão é false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## Veja Também

* Classe [IMathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)