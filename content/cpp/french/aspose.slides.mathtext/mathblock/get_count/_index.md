---
title: get_Count()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection. Lecture seule int32_t.
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() méthode


Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection. Lecture seule **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Remarques


Exemple:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Voir aussi

* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)