---
title: get_Differential()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Différentiel. Lorsque true, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrant), et reçoit l’espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false"
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() méthode


Différentiel. Lorsque true, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrant), et reçoit l’espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## Remarques


Exemple : 
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