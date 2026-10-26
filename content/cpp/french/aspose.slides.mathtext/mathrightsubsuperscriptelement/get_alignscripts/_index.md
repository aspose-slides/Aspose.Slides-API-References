---
title: get_AlignScripts()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie l'alignement des indices/exposants. Lorsque true, les indices et les exposants sont alignés horizontalement l'un par rapport à l'autre. Lorsque false, ils sont ajustés à la forme de la base. La valeur par défaut est false.
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() méthode

Spécifie l'alignement des indices/exposants. Lorsque true, les indices et les exposants sont alignés horizontalement l'un par rapport à l'autre. Lorsque false, ils sont ajustés à la forme de la base. La valeur par défaut est false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Remarques


Exemple:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Voir aussi

* Class [MathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)