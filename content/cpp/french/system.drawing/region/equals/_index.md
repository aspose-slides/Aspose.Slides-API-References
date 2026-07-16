---
title: Equals()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si la région spécifiée est identique à la région représentée par l'objet actuel sur la surface de dessin spécifiée.
type: docs
weight: 157
url: /fr/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) méthode


Détermine si la région spécifiée est identique à la région représentée par l’objet actuel sur la surface de dessin spécifiée.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | La région à comparer avec cette région |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Une surface de dessin |

### Valeur de retour

True si l’intérieur de la région spécifiée est identique à l’intérieur de la région représentée par l’objet actuel lorsque la transformation associée au paramètre **g** est appliquée ; sinon - false

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../)
* Classe [Graphics](../../graphics/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)