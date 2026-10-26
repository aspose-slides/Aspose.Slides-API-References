---
title: Join()
second_title: Référence de l'API Aspose.Slides pour C++
description: Joint un élément mathématique et forme un bloc mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) méthode


Joint un élément mathématique et forme un bloc mathématique

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément à joindre |

### Valeur de retour

Un nouveau [IMathBlock](../../imathblock/) contenant cette instance et l'argument spécifié
## Remarques



Exemple : 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) méthode


Joint un texte mathématique et forme un bloc mathématique

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texte mathématique à joindre |

### Valeur de retour

Un nouveau [IMathBlock](../../imathblock/) contenant cette instance et l'argument spécifié
## Remarques



Exemple : 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)