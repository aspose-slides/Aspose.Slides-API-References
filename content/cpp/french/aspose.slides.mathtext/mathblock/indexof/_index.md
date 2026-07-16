---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine l'index d'un élément mathématique spécifique dans la collection.
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) méthode


Détermine l'index d'un élément mathématique spécifique dans la collection.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément à localiser dans la collection. |

### Valeur de retour

L'index de *item* s'il est trouvé dans la collection ; sinon, -1.
## Remarques



Exemple :
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)