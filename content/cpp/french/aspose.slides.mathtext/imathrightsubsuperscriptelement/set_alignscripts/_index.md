---
title: set_AlignScripts()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie l'alignement des indices/exposants. Lorsque true, les indices et exposants sont alignés horizontalement les uns par rapport aux autres. Lorsque false, ils sont ajustés à la forme de la base. Valeur par défaut est false.
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) méthode


Spécifie l'alignement des indices/exposants. Lorsque true, les indices et exposants sont alignés horizontalement les uns par rapport aux autres. Lorsque false, ils sont ajustés à la forme de la base. La valeur par défaut est false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* Classe [IMathRightSubSuperscriptElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)