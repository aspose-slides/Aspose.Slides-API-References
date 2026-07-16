---
title: get_InkEffect()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient le type d'effet d'encre (p. ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. La valeur est extraite de la propriété du pinceau \"inkEffects\". Si aucun effet reconnu n'est spécifié, InkEffectType::NotDefined est renvoyé."
type: docs
weight: 53
url: /fr/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() méthode


Obtient le type d'effet d'encre (p. ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. La valeur est extraite de la propriete du pinceau \"inkEffects\". Si aucun effet reconnu n'est specifie, [InkEffectType::NotDefined](../../inkeffecttype/) est renvoye.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Voir aussi

* Enum [InkEffectType](../../inkeffecttype/)
* Classe [IInkBrush](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliotheque [Aspose.Slides](../../../)