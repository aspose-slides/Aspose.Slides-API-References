---
title: ToMathArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Place dans un tableau vertical
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() méthode


Place dans un tableau vertical

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
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
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)