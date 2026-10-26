---
title: get_Degree()
second_title: Référence API Aspose.Slides pour C++
description: Argument de degré
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() méthode


Argument de degré

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Remarques


Exemple:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // racine cubique
auto degreeElem = radical->get_Degree();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRadical](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)