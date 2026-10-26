---
title: get_GrowToMatchOperandHeight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque la valeur est vraie, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est vraie
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() méthode


Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque la valeur est vraie, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est vraie.

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Remarques


Exemple:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)