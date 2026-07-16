---
title: get_AlignScripts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie l'alignement des indices/exposants. Lorsque true, les indices et les exposants sont alignés horizontalement les uns par rapport aux autres. Lorsque false, ils sont ajustés à la forme de la base. La valeur par défaut est false.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() méthode


Spécifie l'alignement des indices et des exposants. Lorsque la valeur est vraie, les indices et les exposants sont alignés horizontalement l'un par rapport à l'autre. Lorsque la valeur est fausse, ils sont ajustés à la forme de la base. La valeur par défaut est false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## Remarques


Exemple :
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Voir aussi

* Classe [IMathRightSubSuperscriptElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)