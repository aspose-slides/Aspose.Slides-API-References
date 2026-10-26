---
title: MathPhantom()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe MathPhantom en utilisant l'élément mathématique de base spécifié.
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructeur


Initialise une nouvelle instance de la classe [MathPhantom](../) en utilisant l'élément mathématique de base spécifié.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Le [IMathElement](../../imathelement/) de base dont la visibilité et la disposition seront contrôlées par le fantôme. Cet élément définit le contenu qui peut être masqué ou affiché, tout en affectant l'alignement géométrique des mathématiques environnantes. |
## Remarques



L'élément fantôme est utilisé pour réserver ou supprimer l'espace visuel de son expression de base sans nécessairement l'afficher. Il correspond à l'élément OMML **<m:phant>**. 

Exemple :
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathPhantom](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)