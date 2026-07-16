---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: L'argument auquel l'accent a été appliqué
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() méthode

L'argument auquel l'accent a été appliqué

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Remarques

Exemple:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)