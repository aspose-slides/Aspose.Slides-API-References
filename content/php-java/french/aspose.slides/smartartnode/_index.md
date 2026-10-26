---
title: SmartArtNode
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/smartartnode/
---
## classe SmartArtNode

 Représente un nœud d'un objet SmartArt
 
### getBulletFillFormat {#getBulletFillFormat}

| Name | Description |
| --- | --- |
| getBulletFillFormat () | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour le puce d'un nœud. Remarque : peut renvoyer null pour certains types de mise en page SmartArt qui ne fournissent pas de puces pour les nœuds. Lecture seule IFillFormat. |

 **Renvoie :**
[FillFormat](../fillformat)


---


### getChildNodes {#getChildNodes}

| Name | Description |
| --- | --- |
| getChildNodes () | Renvoie les collections de tous les nœuds enfants du nœud actuel. Lecture seule ISmartArtNodeCollection. |

 **Renvoie :**
[SmartArtNodeCollection](../smartartnodecollection)


---


### getLevel {#getLevel}

| Name | Description |
| --- | --- |
| getLevel () | Renvoie le niveau d'imbrication du nœud. Lecture seule int. |

 **Renvoie :**
int


---


### getOrganizationChartLayout {#getOrganizationChartLayout}

| Name | Description |
| --- | --- |
| getOrganizationChartLayout () | Renvoie ou définit le type de disposition du diagramme d'organisation associé au nœud actuel. Lecture/écriture OrganizationChartLayoutType. |

 **Renvoie :**
int


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int. |

 **Renvoie :**
int

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | la valeur est inférieure à 0. -ou- la valeur est égale ou supérieure au nombre de frères |


---


### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes () | Renvoie les collections de toutes les formes associées au nœud. Lecture seule ISmartArtShapeCollection. |

 **Renvoie :**
[SmartArtShapeCollection](../smartartshapecollection)


---


### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame () | Renvoie le cadre de texte du nœud. Lecture seule ITextFrame. |

 **Renvoie :**
[TextFrame](../textframe)


---


### isAssistant {#isAssistant}

| Name | Description |
| --- | --- |
| isAssistant () | Renvoie ou définit le nœud comme assistant. Lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### isHidden {#isHidden}

| Name | Description |
| --- | --- |
| isHidden () | Renvoie true si ce nœud est un nœud masqué dans le modèle de données. Lecture seule boolean. |

 **Renvoie :**
boolean


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Supprime le nœud actuel. |

 **Renvoie :**
boolean


---


### setAssistant {#setAssistant}

| Name | Description |
| --- | --- |
| setAssistant (boolean) | Renvoie ou définit le nœud comme assistant. Lecture/écriture boolean. |

 **Renvoie :**
void


---


### setOrganizationChartLayout {#setOrganizationChartLayout}

| Name | Description |
| --- | --- |
| setOrganizationChartLayout (int) | Renvoie ou définit le type de disposition du diagramme d'organisation associé au nœud actuel. Lecture/écriture OrganizationChartLayoutType. |

 **Renvoie :**
void


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (int) | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | la valeur est inférieure à 0. -ou- la valeur est égale ou supérieure au nombre de frères |


---  