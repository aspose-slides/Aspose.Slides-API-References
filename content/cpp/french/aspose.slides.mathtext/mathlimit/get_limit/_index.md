---
title: get_Limit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de limite
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() méthode


Argument de limite

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Remarques


Exemple: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)