---
title: MasterNotesSlide
second_title: Référence API Java d'Aspose.Slides pour PHP
description: 
type: docs

url: /fr/aspose.slides/masternotesslide/
---
## classe MasterNotesSlide

 Représente la diapositive maître pour les notes.
 
### getDrawingGuides {#getDrawingGuides}}

| Nom | Description |
| --- | --- |
| getDrawingGuides () | Renvoie une collection de guides de dessin pour la diapositive maître des notes. Lecture seule IDrawingGuidesCollection |

 **Retour :**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}}

| Nom | Description |
| --- | --- |
| getHeaderFooterManager () | Renvoie le gestionnaire HeaderFooter de la diapositive maître des notes. Lecture seule IMasterHandoutSlideHeaderFooterManager. |

 **Retour :**
[MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager)


---


### getNotesStyle {#getNotesStyle}}

| Nom | Description |
| --- | --- |
| getNotesStyle () | Renvoie le style d'un texte de notes. Lecture seule ITextStyle. |

 **Retour :**
[TextStyle](../textstyle)


---


### getShowMasterShapes {#getShowMasterShapes}}

| Nom | Description |
| --- | --- |
| getShowMasterShapes () | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture booléen. |

 **Retour :**
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Lancée si la valeur true est définie pour la diapositive maître. |


---


### getThemeManager {#getThemeManager}}

| Nom | Description |
| --- | --- |
| getThemeManager () | Renvoie le gestionnaire de thème. Lecture seule IMasterThemeManager. |

 **Retour :**
[MasterThemeManager](../masterthememanager)


---


### setShowMasterShapes {#setShowMasterShapes}}

| Nom | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture booléen. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Lancée si la valeur true est définie pour la diapositive maître. |


---