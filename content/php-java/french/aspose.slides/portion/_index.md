---
title: Portion
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/portion/
---
## Portion classe

 Représente une partie de texte à l'intérieur d'un paragraphe de texte.
 
### Portion {#Portion}

| Nom | Description |
| --- | --- |
| Portion() | Initialise une nouvelle instance de la classe Portion. |

 **Retour:**  
Portion


---


### Portion {#Portion}

| Nom | Description |
| --- | --- |
| Portion(String) | Initialise une nouvelle instance de la classe Portion. |

 **Retour:**  
Portion


---


### Portion {#Portion}

| Nom | Description |
| --- | --- |
| Portion([Portion](../portion)) | Initialise une nouvelle instance de la classe Portion. |

 **Retour:**  
Portion


---


### addField {#addField}

| Nom | Description |
| --- | --- |
| addField ([FieldType](../fieldtype)) | Convertit cette portion en champ mis à jour automatiquement. |

 **Retour:**  
void


---


### addField {#addField}

| Nom | Description |
| --- | --- |
| addField (String) | Convertit cette portion en champ mis à jour automatiquement. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| internalString | String | Nom interne du type FieldType. |

 **Retour:**  
void


---


### getCoordinates {#getCoordinates}

| Nom | Description |
| --- | --- |
| getCoordinates () | Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère, y compris le débordement latéral gauche. La coordonnée Y comprend le débordement latéral supérieur. |

 **Retour:**  
Point2D.Float


---


### getField {#getField}

| Nom | Description |
| --- | --- |
| getField () | Retourne un champ de cette portion. Lecture seule IField. |

 **Retour:**  
[Field](../field)


---


### getPortionFormat {#getPortionFormat}

| Nom | Description |
| --- | --- |
| getPortionFormat () | Retourne un objet de mise en forme qui contient les propriétés de mise en forme explicitement définies de la portion de texte sans héritage appliqué. Lecture seule IPortionFormat. L'objet de mise en forme contient les paramètres de mise en forme définis uniquement pour la portion actuelle, les données héritées n'étant pas appliquées. Pour obtenir les valeurs effectives incluant celles héritées, utilisez la méthode PortionFormat#getEffective. |

 **Retour:**  
[PortionFormat](../portionformat)


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Retourne la présentation parente d'un texte. Lecture seule IPresentation. |

 **Retour:**  
[Presentation](../presentation)


---


### getRect {#getRect}

| Nom | Description |
| --- | --- |
| getRect () | Obtient les coordonnées du rectangle qui encadre la portion. Le rectangle comprend toutes les lignes de texte de la portion, y compris les lignes vides. |

 **Retour:**  
Rectangle2D.Float


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Retourne la diapositive parente d'un texte. Lecture seule BaseSlide. |

 **Retour:**  
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Nom | Description |
| --- | --- |
| getText () | Obtient ou définit le texte brut d'une portion. Lecture/écriture String. Valeur : Le texte. |

 **Retour:**  
String


---


### removeField {#removeField}

| Nom | Description |
| --- | --- |
| removeField () | Convertit cette portion de champ en une portion simple. |

 **Retour:**  
void


---


### setText {#setText}

| Nom | Description |
| --- | --- |
| setText (String) | Obtient ou définit le texte brut d'une portion. Lecture/écriture String. Valeur : Le texte. |

 **Retour:**  
void


---