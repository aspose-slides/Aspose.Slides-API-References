---
title: idx_set()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit IMathElement à l'index spécifié.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) méthode

Définit [IMathElement](../../imathelement/) à l'index spécifié.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de l'élément |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément mathématique. |
## Remarques



Exemple:
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