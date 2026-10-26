---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère IMathElement à l'index spécifié.
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) méthode

Obtient [IMathElement](../../imathelement/) à l'index spécifié.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de l'élément |

### Valeur de retour

L'élément mathématique.
## Remarques



Exemple :
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)