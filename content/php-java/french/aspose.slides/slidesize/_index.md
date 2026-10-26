---
title: SlideSize
second_title: Référence de l'API Aspose.Sildes pour PHP via Java
description: 
type: docs

url: /fr/aspose.slides/slidesize/
---
## SlideSize classe

 Représente la taille et l'orientation d'une diapositive.
 
### getOrientation {#getOrientation}

| Name | Description |
| --- | --- |
| getOrientation () | Obtient ou définit l'orientation de la diapositive. Modifier cette valeur échange la largeur et la hauteur de la diapositive. |

 **Retour :**
int


---


### getSize {#getSize}

| Name | Description |
| --- | --- |
| getSize () | Obtient les dimensions de la diapositive en points. Attribuer une nouvelle valeur réinitialise la propriété #getType à SlideSizeType#Custom et définit #getOrientation/ #setOrientation(int). |

 **Retour :**
Dimension2D


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Obtient le type de taille de la diapositive. Affecter une valeur autre que SlideSizeType#Custom ajuste #getSize selon les dimensions prédéfinies, tout en conservant #getOrientation/ #setOrientation(int). |

 **Retour :**
int


---


### setOrientation {#setOrientation}

| Name | Description |
| --- | --- |
| setOrientation (int) | Obtient ou définit l'orientation de la diapositive. Modifier cette valeur échange la largeur et la hauteur de la diapositive. |

 **Retour :**
void


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize (int, int) | Définit la taille de la diapositive par type et met à l'échelle le contenu existant. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| type | int | La taille de diapositive prédéfinie à appliquer. |
| scaleType | int | Le mode de redimensionnement du contenu à utiliser. Affecter une valeur autre que SlideSizeType#Custom ajuste #getSize en fonction du type sélectionné, tout en préservant #getOrientation/ #setOrientation(int). |

 **Retour :**
void


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize (float, float, int) | Définit explicitement les dimensions de la diapositive et met à l'échelle le contenu existant. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| width | float | La nouvelle largeur de la diapositive, en points. |
| height | float | La nouvelle hauteur de la diapositive, en points. |
| scaleType | int | Le mode de redimensionnement du contenu à utiliser. Cela réinitialise la propriété #getType à SlideSizeType#Custom et définit #getOrientation/ #setOrientation(int). |

 **Retour :**
void


---