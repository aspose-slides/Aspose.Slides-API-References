---
title: ShapeElement class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapeelement/
---
## ShapeElement classe

Représente une partie d’une forme avec les mêmes propriétés de contour et de remplissage.

Le type ShapeElement expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/fr/aspose.slides/shapeelement/parent_shape/) | Renvoie un Shape_PPT pour lequel l'élément a été créé.<br/>            Lecture seule [`Shape`](/slides/python-net/fr/aspose.slides/shape). |
| [`path_points`](/slides/python-net/fr/aspose.slides/shapeelement/path_points/) | Obtient un tableau de points qui définissent la géométrie du tracé de l'élément. |
| [`path_types`](/slides/python-net/fr/aspose.slides/shapeelement/path_types/) | Obtient un tableau de valeurs d'octet qui spécifient le type de chaque point du tracé de l'élément. <br/>            <br/>**0**  Indique que le point est le début d'une figure.<br/><br/><br/>**1**  Indique que le point est l'une des deux extrémités d'une ligne.<br/><br/><br/>**3**  Indique que le point est une extrémité ou un point de contrôle d'une courbe de Bézier cubique.<br/><br/><br/>**7**  Masque tous les bits sauf les trois bits de poids faible, qui indiquent le type de point.<br/><br/><br/>**16**  Spécifie que le segment correspondant est en pointillés.<br/><br/><br/>**32**  Spécifie que le point est un marqueur.<br/><br/><br/>**128**  Spécifie que le point est le dernier point d'un sous-chemin fermé (figure).<br/><br/><br/>**129**  Indique un point de données qui est à la fois une extrémité de segment de ligne et le dernier point d'un sous-chemin fermé. |
| [`fill_source`](/slides/python-net/fr/aspose.slides/shapeelement/fill_source/) | Renvoie des informations sur la façon de remplir un élément.<br/>            Lecture seule [`ShapeElementFillSource`](/slides/python-net/fr/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/fr/aspose.slides/shapeelement/stroke_source/) | Renvoie des informations sur la façon de tracer un élément.<br/>            Lecture seule [`ShapeElementStrokeSource`](/slides/python-net/fr/aspose.slides/shapeelementstrokesource). |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)