---
title: set_Differential()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Différentiel Lorsque true, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrand), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Par défaut : false"
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) méthode


Differential Lorsque true, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uDC65 dans un intégrand), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Par défaut : false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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

* Classe [MathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)