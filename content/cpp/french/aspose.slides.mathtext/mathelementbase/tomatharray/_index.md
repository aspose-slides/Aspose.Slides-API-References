---
title: ToMathArray()
second_title: Aspose.Slides pour la référence API C++
description: Place dans un tableau vertical
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() méthode


Place dans un tableau vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Valeur de retour

Nouvelle instance du type [IMathArray](../../imatharray/)
## Remarques



Exemple: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [MathElementBase](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)