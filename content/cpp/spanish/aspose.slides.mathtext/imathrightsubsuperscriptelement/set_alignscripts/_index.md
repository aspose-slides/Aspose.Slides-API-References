---
title: set_AlignScripts()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la alineación de subíndice/superíndice. Cuando true, subíndice y superíndice se alinean horizontalmente entre sí. Cuando false, se ajustan a la forma de la base. El valor predeterminado es false.
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) método


Especifica la alineación de subíndice/superíndice. Cuando true, subíndice y superíndice se alinean horizontalmente entre sí. Cuando false, se ajustan a la forma de la base. El valor predeterminado es false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* Clase [IMathRightSubSuperscriptElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)