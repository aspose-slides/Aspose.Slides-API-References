---
title: Join()
second_title: Référence de l'API Aspose.Slides pour C++
description: Joint un élément mathématique à ce bloc mathématique
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) méthode


Joint un élément mathématique à ce bloc mathématique

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément à joindre |

### Valeur de retour

L'instance actuelle de [IMathBlock](../../imathblock/)
## Remarques



Exemple : 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) méthode


Joint un texte mathématique à ce bloc mathématique

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texte mathématique à joindre |

### Valeur de retour

Un nouveau [IMathBlock](../../imathblock/) contenant cette instance et l'argument spécifié
## Remarques



Exemple : 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)