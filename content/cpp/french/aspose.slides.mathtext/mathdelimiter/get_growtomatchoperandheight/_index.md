---
title: get_GrowToMatchOperandHeight()
second_title: Référence API Aspose.Slides for C++
description: Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter Lorsque true, les délimiteurs grandissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() méthode

Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter Lorsque true, les délimiteurs grandissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Remarques

Exemple :
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)