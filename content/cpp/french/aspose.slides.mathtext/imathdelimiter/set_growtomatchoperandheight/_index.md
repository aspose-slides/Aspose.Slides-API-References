---
title: set_GrowToMatchOperandHeight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque true, les délimiteurs croissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) méthode

Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque true, les délimiteurs croissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Remarques

Exemple :
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Voir aussi

* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)