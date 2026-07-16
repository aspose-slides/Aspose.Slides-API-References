---
title: get_Arguments()
second_title: Référence de l'API Aspose.Slides pour C++
description: Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() méthode


Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Remarques


Exemple:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)