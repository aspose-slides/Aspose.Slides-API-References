---
title: RemoveAt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'élément à l'index spécifié de la collection.
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) méthode

Supprime l'élément à l'index spécifié de la collection.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de l'élément à supprimer. |
## Remarques



Exemple : 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Voir aussi

* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)