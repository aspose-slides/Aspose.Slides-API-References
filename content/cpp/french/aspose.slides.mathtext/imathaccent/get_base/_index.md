---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: L'argument auquel l'accent a été appliqué
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() méthode


L'argument auquel l'accent a été appliqué

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* Classe [IMathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)