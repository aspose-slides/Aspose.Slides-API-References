---
title: get_Degree()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument du degré
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() méthode


Degree argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Remarques


Exemple: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)