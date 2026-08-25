---
title: Paragraph
second_title: Référence de l'API Java Aspose.Slides pour PHP
description: 
type: docs

url: /fr/aspose.slides/paragraph/
---
## Classe Paragraph

 Représente un paragraphe de texte.
 
### Paragraph {#Paragraph}

| Name | Description |
| --- | --- |
| Paragraph() | Initializes a new instance of the Paragraph class with default properties. |

 **Retour:**
Paragraph


---


### Paragraph {#Paragraph}

| Name | Description |
| --- | --- |
| Paragraph([Paragraph](../paragraph)) | Fonction de copie qui initialise une nouvelle instance de la classe Paragraph. |

 **Retour:**
Paragraph


---


### getEndParagraphPortionFormat {#getEndParagraphPortionFormat}

| Name | Description |
| --- | --- |
| getEndParagraphPortionFormat () | Spécifie les propriétés de portion qui doivent être utilisées si une autre portion est insérée après la dernière. |

 **Retour:**
[PortionFormat](../portionformat)


---


### getLinesCount {#getLinesCount}

| Name | Description |
| --- | --- |
| getLinesCount () | Obtient le nombre de lignes dans un paragraphe. |

 **Retour:**
int


---


### getParagraphFormat {#getParagraphFormat}

| Name | Description |
| --- | --- |
| getParagraphFormat () | Retourne l'objet de formatage pour ce paragraphe. Lecture seule IParagraphFormat. L'objet de formatage contient les paramètres de formatage définis uniquement pour le paragraphe actuel, les données héritées ne sont pas appliquées. Pour obtenir les valeurs effectives, y compris celles héritées, utilisez la méthode ParagraphFormat#getEffective. |

 **Retour:**
[ParagraphFormat](../paragraphformat)


---


### getPortions {#getPortions}

| Name | Description |
| --- | --- |
| getPortions () | Retourne la collection de portions de texte. Lecture seule IPortionCollection. |

 **Retour:**
[PortionCollection](../portioncollection)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Retourne la présentation parente d'un paragraphe. Lecture seule IPresentation. |

 **Retour:**
[Presentation](../presentation)


---


### getRect {#getRect}

| Name | Description |
| --- | --- |
| getRect () | Obtient les coordonnées du rectangle qui encadre le paragraphe. Le rectangle inclut toutes les lignes de texte du paragraphe, y compris les lignes vides. |

 **Retour:**
Rectangle2D.Float


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Retourne la diapositive parente d'un paragraphe. Lecture seule BaseSlide. |

 **Retour:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Obtient ou définit le texte brut d'un paragraphe. Lecture/écriture String. Valeur : le texte. |

 **Retour:**
String


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Fusionne les portions avec le même formatage. |

 **Retour:**
void


---


### setEndParagraphPortionFormat {#setEndParagraphPortionFormat}

| Name | Description |
| --- | --- |
| setEndParagraphPortionFormat ([PortionFormat](../portionformat)) | Spécifie les propriétés de portion qui doivent être utilisées si une autre portion est insérée après la dernière. |

 **Retour:**
void


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Obtient ou définit le texte brut d'un paragraphe. Lecture/écriture String. Valeur : le texte. |

 **Retour:**
void


---