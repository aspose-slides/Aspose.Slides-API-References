---
title: get_AlignScripts()
second_title: Aspose.Slides para Referência da API C++
description: Especifica o alinhamento de subscrito/sobrescrito. Quando true, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando false, eles são ajustados ao formato da base. O valor padrão é false.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() método

Especifica o alinhamento do subscrito/sobrescrito. Quando true, o subscrito e o sobrescrito são alinhados horizontalmente entre si. Quando false, eles são ajustados ao formato da base. O valor padrão é false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* Classe [MathRightSubSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)