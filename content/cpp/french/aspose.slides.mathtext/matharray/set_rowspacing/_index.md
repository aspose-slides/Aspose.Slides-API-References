---
title: set_RowSpacing()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Espacement entre les lignes d'un tableau Il est utilisé uniquement lorsque RowSpacingRule est réglé à 3 Exactement dans ce cas l'unité de mesure est les points ou Multiple dans ce cas l'unité de mesure est les demi-lignes. Par défaut: 0"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) méthode


Espacement entre les lignes d'un tableau. Il est utilisé uniquement lorsque RowSpacingRule est réglé à 3, exactement dans ce cas l'unité de mesure est les points ou Multiple, dans ce cas l'unité de mesure est les demi-lignes. Par défaut : 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Remarques


Exemple :
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Voir aussi

* Classe [MathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)