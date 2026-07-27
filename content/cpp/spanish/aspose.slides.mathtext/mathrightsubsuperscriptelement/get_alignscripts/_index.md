---
title: get_AlignScripts()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la alineación de subíndice/superíndice. Cuando es true, subíndice y superíndice están alineados horizontalmente entre sí. Cuando es false, se ajustan a la forma de la base. El valor predeterminado es false.
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() método


Especifica la alineación de subíndice/superíndice. Cuando es true, subíndice y superíndice están alineados horizontalmente entre sí. Cuando es false, están ajustados a la forma de la base. El valor predeterminado es false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Observaciones


Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Ver también

* Clase [MathRightSubSuperscriptElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)