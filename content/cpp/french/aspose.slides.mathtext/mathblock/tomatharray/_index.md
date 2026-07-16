---
title: ToMathArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Place les éléments enfants dans un tableau vertical
type: docs
weight: 235
url: /fr/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() méthode


Place les éléments enfants dans un tableau vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Valeur de retour

Nouvelle instance du type [IMathArray](../../imatharray/)
## Remarques



Exemple :
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)