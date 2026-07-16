---
title: get_PathTypes()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un tableau de valeurs d'octet qui spécifient le type de chaque point dans le chemin de l'élément.
type: docs
weight: 27
url: /fr/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() méthode

Renvoie un tableau de valeurs d'octet qui spécifient le type de chaque point dans le chemin de l'élément.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Remarques

**0** Indique que le point est le début d'une figure.

**1** Indique que le point est l'un des deux points d'extrémité d'une ligne.

**3** Indique que le point est un point d'extrémité ou un point de contrôle d'une spline de Bézier cubique.

**7** Masque tous les bits sauf les trois bits de poids faible, qui indiquent le type du point.

**16** Spécifie que le segment correspondant est en pointillé.

**32** Spécifie que le point est un repère.

**128** Spécifie que le point est le dernier point d'un sous-chemin fermé (figure).

**129** Indique un point de données qui est à la fois un point d'extrémité de segment de ligne et le dernier point d'un sous-chemin fermé.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ShapeElement](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)