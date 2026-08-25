---
title: GeometryPath
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/geometrypath/
---
## GeometryPath classe

 Représente le chemin géométrique de GeometryShape
 
### GeometryPath {#GeometryPath}

| Nom | Description |
| --- | --- |
| GeometryPath() | Crée une instance de GeometryPath |

 **Renvoie:**  
GeometryPath


---

### arcTo {#arcTo}

| Nom | Description |
| --- | --- |
| arcTo (float, float, float, float) | Ajoute l'arc spécifié au chemin. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| width | float | Largeur du rectangle |
| heigth | float | Hauteur du rectangle |
| startAngle | float | Angle de départ. |
| sweepAngle | float | Angle d'étendue |

 **Renvoie:**  
void


---

### closeFigure {#closeFigure}

| Nom | Description |
| --- | --- |
| closeFigure () | Ferme la figure actuelle de ce chemin |

 **Renvoie:**  
void


---

### cubicBezierTo {#cubicBezierTo}

| Nom | Description |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float) | Ajoute une courbe de Bézier cubique à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Premier point de direction |
| point2 | Point2D.Float | Deuxième point de direction |
| point3 | Point2D.Float | Point d'arrivée |

 **Renvoie:**  
void


---

### cubicBezierTo {#cubicBezierTo}

| Nom | Description |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float) | Ajoute une courbe de Bézier cubique à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point d'arrivée |
| y3 | float | Coordonnée Y du point d'arrivée |

 **Renvoie:**  
void


---

### cubicBezierTo {#cubicBezierTo}

| Nom | Description |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float, long) | Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Premier point de direction |
| point2 | Point2D.Float | Deuxième point de direction |
| point3 | Point2D.Float | Point d'arrivée |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### cubicBezierTo {#cubicBezierTo}

| Nom | Description |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float, long) | Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point d'arrivée |
| y3 | float | Coordonnée Y du point d'arrivée |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### getFillMode {#getFillMode}

| Nom | Description |
| --- | --- |
| getFillMode () | Définit le mode de remplissage |

 **Renvoie:**  
byte


---

### getPathData {#getPathData}

| Nom | Description |
| --- | --- |
| getPathData () | Renvoie le chemin géométrique de GeometryShape sous forme d'un tableau de segments de chemin. |

 **Renvoie:**  
[PathSegment](../pathsegment)


---

### getStroke {#getStroke}

| Nom | Description |
| --- | --- |
| getStroke () | Définit l'apparence du contour |

 **Renvoie:**  
boolean


---

### lineTo {#lineTo}

| Nom | Description |
| --- | --- |
| lineTo (Point2D.Float) | Ajoute une ligne à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | Point d'arrivée de la ligne |

 **Renvoie:**  
void


---

### lineTo {#lineTo}

| Nom | Description |
| --- | --- |
| lineTo (float, float) | Ajoute une ligne à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point d'arrivée de la ligne |
| y | float | Coordonnée Y du point d'arrivée de la ligne |

 **Renvoie:**  
void


---

### lineTo {#lineTo}

| Nom | Description |
| --- | --- |
| lineTo (Point2D.Float, long) | Ajoute une ligne à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | Point d'arrivée |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### lineTo {#lineTo}

| Nom | Description |
| --- | --- |
| lineTo (float, float, long) | Ajoute une ligne à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### moveTo {#moveTo}

| Nom | Description |
| --- | --- |
| moveTo (Point2D.Float) | Définit la position du point suivant. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | Position du point |

 **Renvoie:**  
void


---

### moveTo {#moveTo}

| Nom | Description |
| --- | --- |
| moveTo (float, float) | Définit la position du point suivant. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |

 **Renvoie:**  
void


---

### quadraticBezierTo {#quadraticBezierTo}

| Nom | Description |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float) | Ajoute une courbe de Bézier quadratique à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Point de direction |
| point2 | Point2D.Float | Point d'arrivée |

 **Renvoie:**  
void


---

### quadraticBezierTo {#quadraticBezierTo}

| Nom | Description |
| --- | --- |
| quadraticBezierTo (float, float, float, float) | Ajoute une courbe de Bézier quadratique à la fin du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point d'arrivée |
| y2 | float | Coordonnée Y du point d'arrivée |

 **Renvoie:**  
void


---

### quadraticBezierTo {#quadraticBezierTo}

| Nom | Description |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float, long) | Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Point de direction |
| point2 | Point2D.Float | Point d'arrivée |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### quadraticBezierTo {#quadraticBezierTo}

| Nom | Description |
| --- | --- |
| quadraticBezierTo (float, float, float, float, long) | Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point d'arrivée |
| y2 | float | Coordonnée Y du point d'arrivée |
| index | long | Index du segment dans PathData |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L'index du segment est hors de la plage de PathData |


---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime le segment à l'index spécifié du chemin géométrique. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index du chemin géométrique à supprimer. |

 **Renvoie:**  
void


---

### setFillMode {#setFillMode}

| Nom | Description |
| --- | --- |
| setFillMode (byte) | Définit le mode de remplissage |

 **Renvoie:**  
void


---

### setStroke {#setStroke}

| Nom | Description |
| --- | --- |
| setStroke (boolean) | Définit l'apparence du contour |

 **Renvoie:**  
void


---