---
title: set_Differential()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Différentiel. Lorsque vrai, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrand), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut: false"
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) méthode


Différentiel. Lorsqu’il est vrai, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrand), et reçoit l’espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Remarques


Exemple: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Voir aussi

* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)