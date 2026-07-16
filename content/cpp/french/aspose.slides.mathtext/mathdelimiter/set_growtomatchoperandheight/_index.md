---
title: set_GrowToMatchOperandHeight()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter Lorsque true, les délimiteurs grandissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) méthode

Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter When true, les délimiteurs s'agrandissent verticalement pour correspondre à la hauteur de leur opérande. La valeur par défaut est true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Remarques

Exemple:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Voir aussi

* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)