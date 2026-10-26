---
title: get_Limit()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Argument de limite
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() méthode


Argument de limite

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Remarques


Exemple: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)