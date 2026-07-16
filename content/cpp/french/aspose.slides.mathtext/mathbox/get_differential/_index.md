---
title: get_Differential()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Differential Lorsqu'elle est vraie, la boîte agit comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Par défaut : false"
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() méthode

Differential Lorsque la valeur est vraie, la boîte se comporte comme un différentiel (par exemple, \\uD835\\uDC51\\uD835\\uDC65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Par défaut : false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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
* Library [Aspose.Slides](../../../)