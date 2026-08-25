---
title: GeometryShape
second_title: Aspose.Sildes pour PHP via la Référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/geometryshape/
---
## GeometryShape classe

 Représente la classe parente de toutes les formes géométriques.
 
### createShapeElements {#createShapeElements}

| Nom | Description |
| --- | --- |
| createShapeElements () | Crée et renvoie un tableau des éléments de la forme. |

 **Retourne :**
[ShapeElement](../shapeelement)


---

### getAdjustments {#getAdjustments}

| Nom | Description |
| --- | --- |
| getAdjustments () | Renvoie une collection des valeurs d'ajustement de la forme. Lecture seule IAdjustValueCollection. |

 **Retourne :**
[AdjustValueCollection](../adjustvaluecollection)


---

### getGeometryPaths {#getGeometryPaths}

| Nom | Description |
| --- | --- |
| getGeometryPaths () | Renvoie une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |

 **Retourne :**
[GeometryPath](../geometrypath)


---

### getShapeStyle {#getShapeStyle}

| Nom | Description |
| --- | --- |
| getShapeStyle () | Renvoie l'objet de style de la forme. Lecture seule IShapeStyle. |

 **Retourne :**
[ShapeStyle](../shapestyle)


---

### getShapeType {#getShapeType}

| Nom | Description |
| --- | --- |
| getShapeType () | Renvoie ou définit le type prédéfini de la géométrie. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture ShapeType. |

 **Retourne :**
int


---

### setGeometryPath {#setGeometryPath}

| Nom | Description |
| --- | --- |
| setGeometryPath ([GeometryPath](../geometrypath)) | Met à jour la géométrie de la forme à partir d'un objet IGeometryPath. Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme (ShapeType( #getShapeType/ #setShapeType(int))) en ShapeType#Custom. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | Chemin géométrique |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Chemin vide trouvé |


---

### setGeometryPaths {#setGeometryPaths}

| Nom | Description |
| --- | --- |
| setGeometryPaths (com.aspose.slides.IGeometryPath[]) | Met à jour la géométrie de la forme à partir d'un tableau d'IGeometryPath. Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme (ShapeType( #getShapeType/ #setShapeType(int))) en ShapeType#Custom. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Tableau de chemins géométriques |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Chemin vide |


---

### setShapeType {#setShapeType}

| Nom | Description |
| --- | --- |
| setShapeType (int) | Renvoie ou définit le type prédéfini de la géométrie. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture ShapeType. |

 **Retourne :**
void


---