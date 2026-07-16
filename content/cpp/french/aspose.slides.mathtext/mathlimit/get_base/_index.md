---
title: get_Base()
second_title: Référence API Aspose.Slides for C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() méthode

argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Remarques

Exemple :
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)