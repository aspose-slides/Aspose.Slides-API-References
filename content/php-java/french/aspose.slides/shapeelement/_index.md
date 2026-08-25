---
title: ShapeElement
second_title: Référence de l'API Java pour Aspose.Sildes via PHP
description: 
type: docs
url: /fr/aspose.slides/shapeelement/
---
## ShapeElement classe

 Représente une partie d'une forme avec les mêmes propriétés de contour et de remplissage.

### getFillSource {#getFillSource}

| Nom | Description |
| --- | --- |
| getFillSource () | Renvoie des informations sur la façon de remplir un élément. Read-only ShapeElementFillSource. |

 **Retour:**  
byte


---

### getParentShape {#getParentShape}

| Nom | Description |
| --- | --- |
| getParentShape () | Renvoie un Shape_PPT pour lequel l'élément a été créé. Read-only Shape. |

 **Retour:**  
Shape


---

### getPathPoints {#getPathPoints}

| Nom | Description |
| --- | --- |
| getPathPoints () | Obtient un tableau de points qui définissent la géométrie du chemin de l'élément. |

 **Retour:**  
Point2D.Float


---

### getPathTypes {#getPathTypes}

| Nom | Description |
| --- | --- |
| getPathTypes () | Obtient un tableau de valeurs byte qui spécifient le type de chaque point dans le chemin de l'élément. 0 Indique que le point est le début d'une figure. 1 Indique que le point est l'une des deux extrémités d'une ligne. 3 Indique que le point est une extrémité ou un point de contrôle d'une courbe de Bézier cubique. 7 Masque tous les bits sauf les trois bits de poids faible, qui indiquent le type de point. 16 Spécifie que le segment correspondant est en pointillés. 32 Spécifie que le point est un marqueur. 128 Spécifie que le point est le dernier point d'un sous-chemin fermé (figure). 129 Indique un point de données qui est à la fois l'extrémité d'un segment de ligne et le dernier point d'un sous-chemin fermé. |

 **Retour:**  
byte


---

### getStrokeSource {#getStrokeSource}

| Nom | Description |
| --- | --- |
| getStrokeSource () | Renvoie des informations sur la façon de tracer un élément. Read-only ShapeElementStrokeSource. |

 **Retour:**  
byte


---