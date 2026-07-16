---
title: MathSubscriptElement()
second_title: Référence API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe MathSubscriptElement.
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructeur


Initialise une nouvelle instance de la classe [MathSubscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathSubscriptElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)