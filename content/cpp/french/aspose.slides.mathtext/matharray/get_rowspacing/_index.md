---
title: get_RowSpacing()
second_title: Référence API Aspose.Slides pour C++
description: "Espacement entre les lignes d'un tableau Il est utilisé uniquement lorsque RowSpacingRule est réglé sur 3 Exactement dans ce cas l'unité de mesure est les points ou Multiple dans ce cas l'unité de mesure est les demi-lignes. Valeur par défaut: 0"
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() méthode

Espacement entre les lignes d'un tableau Il est utilisé uniquement lorsque RowSpacingRule est réglé sur 3 Exactement dans ce cas l'unité de mesure est les points ou Multiple dans ce cas l'unité de mesure est les demi-lignes. Valeur par défaut: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Remarques

Exemple:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Voir aussi

* Classe [MathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)