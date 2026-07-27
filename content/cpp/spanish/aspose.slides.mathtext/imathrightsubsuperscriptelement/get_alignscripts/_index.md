---
title: get_AlignScripts()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la alineación del subíndice/superíndice. Cuando true, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando false, se ajustan a la forma de la base. El valor predeterminado es false.
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() método


Especifica la alineación del subíndice/superíndice. Cuando true, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando false, están ajustados al contorno de la base. El valor predeterminado es false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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