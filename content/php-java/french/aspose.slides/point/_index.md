---
title: Point
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/point/
---
## Point classe

 Représente un point d'animation.
 
### Point {#Point}

| Nom | Description |
| --- | --- |
| Point() | Fonction par défaut. |

 **Retourne :**
Point


---


### Point {#Point}

| Nom | Description |
| --- | --- |
| Point(float, Object, String) | Crée un point d'animation avec le temps, la valeur et la formule. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| time | float | Valeur du temps. |
| value | Object | Valeur du point. |
| formula | String | Formule. |

 **Retourne :**
Point


---


### getFormula {#getFormula}

| Nom | Description |
| --- | --- |
| getFormula () | Les formules dans les valeurs, les attributs from, to, by peuvent être composées de ces éléments : Opérateurs arithmétiques standards : &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constantes : &#39pi&#39 &#39e&#39 Opérateurs conditionnels : &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Opérateurs de comparaison : &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Opérateurs trigonométriques : &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Logarithme naturel &#39ln()&#39 Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lecture/écriture String. |

 **Retourne :**
String


---


### getTime {#getTime}

| Nom | Description |
| --- | --- |
| getTime () | Représente la valeur du temps. Lecture/écriture float. |

 **Retourne :**
float


---


### getValue {#getValue}

| Nom | Description |
| --- | --- |
| getValue () | Représente la valeur du point. Seulement : bool, ColorFormat, float, int, string. Lecture/écriture Object. |

 **Retourne :**
Object


---


### setFormula {#setFormula}

| Nom | Description |
| --- | --- |
| setFormula (String) | Les formules dans les valeurs, les attributs from, to, by peuvent être composées de ces éléments : Opérateurs arithmétiques standards : &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constantes : &#39pi&#39 &#39e&#39 Opérateurs conditionnels : &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Opérateurs de comparaison : &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Opérateurs trigonométriques : &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Logarithme naturel &#39ln()&#39 Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lecture/écriture String. |

 **Retourne :**
void


---


### setTime {#setTime}

| Nom | Description |
| --- | --- |
| setTime (float) | Représente la valeur du temps. Lecture/écriture float. |

 **Retourne :**
void


---


### setValue {#setValue}

| Nom | Description |
| --- | --- |
| setValue (Object) | Représente la valeur du point. Seulement : bool, ColorFormat, float, int, string. Lecture/écriture Object. |

 **Retourne :**
void


---