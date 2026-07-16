---
title: set_AlignScripts()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Spécifie l'alignement des indices et des exposants. Lorsque true, les indices et les exposants sont alignés horizontalement l'un par rapport à l'autre. Lorsque false, ils sont ajustés à la forme de la base. Valeur par défaut : false.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) méthode

Spécifie l'alignement des indices et des exposants. Lorsque true, les indices et les exposants sont alignés horizontalement l'un par rapport à l'autre. Lorsque false, ils sont ajustés à la forme de la base. La valeur par défaut est false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* Classe [MathRightSubSuperscriptElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)