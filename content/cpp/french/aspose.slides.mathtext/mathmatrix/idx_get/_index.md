---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Élément de la matrice
type: docs
weight: 209
url: /fr/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) méthode


Élément de la matrice

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| row | **int32_t** | The zero-based index of the row to get item |
| column | **int32_t** | The zero-based index of the column to get item |

### Valeur de retour


## Remarques



Exemple: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)