---
title: set_AlignScripts()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la alineación de subíndice/superíndice. Cuando es verdadero, el subíndice y el superíndice se alinean horizontalmente entre sí. Cuando es falso, se ajustan a la forma de la base. El valor predeterminado es falso.
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) método

Especifica la alineación de subíndice/superíndice. Cuando es verdadero, el subíndice y el superíndice se alinean horizontalmente entre sí. Cuando es falso, se ajustan a la forma de la base. El valor predeterminado es falso.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Comentarios

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