---
title: set_RowSpacing()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Espacement entre les lignes d'un tableau. Il n'est utilisé que lorsque RowSpacingRule est défini sur 3, exactement dans ce cas l'unité de mesure est le point ou Multiple dans ce cas l'unité de mesure est la demi-ligne. Valeur par défaut: 0"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) méthode

Espace entre les lignes d'un tableau. Il n'est utilisé que lorsque RowSpacingRule est défini sur 3, exactement dans ce cas l'unité de mesure est le point ou Multiple dans ce cas l'unité de mesure est la demi-ligne. Valeur par défaut: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Remarques

Exemple: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Voir aussi

* Classe [IMathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)