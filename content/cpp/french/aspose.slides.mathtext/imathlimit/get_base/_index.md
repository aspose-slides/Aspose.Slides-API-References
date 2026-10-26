---
title: get_Base()
second_title: Référence de l'API Aspose.Slides for C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() méthode

Argument de base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Remarques

Exemple:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathLimit](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)