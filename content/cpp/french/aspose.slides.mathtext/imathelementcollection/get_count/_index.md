---
title: get_Count()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le nombre d'éléments réellement contenus dans la collection. Lecture seule int32_t.
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() méthode

Renvoie le nombre d'éléments réellement contenus dans la collection. Lecture seule **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```
## Remarques

Exemple :
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```
## Voir aussi

* Classe [IMathElementCollection](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)