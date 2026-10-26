---
title: MasterSlide
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/masterslide/
---
## MasterSlide classe

 Représente une diapositive maître dans une présentation.
 
### applyExternalThemeToDependingSlides {#applyExternalThemeToDependingSlides}

| Nom | Description |
| --- | --- |
| applyExternalThemeToDependingSlides (String) | Crée une nouvelle diapositive maître basée sur celle actuelle, applique un thème externe et applique la diapositive maître créée à toutes les diapositives dépendantes. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier de thème externe (.thmx). |

 **Renvoie:**
[MasterSlide](../masterslide)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxReadException | Lorsque le thème externe ne peut pas être appliqué. |


---


### getBodyStyle {#getBodyStyle}

| Nom | Description |
| --- | --- |
| getBodyStyle () | Renvoie le style d’un texte de corps. Lecture seule ITextStyle. |

 **Renvoie:**
[TextStyle](../textstyle)


---


### getDependingSlides {#getDependingSlides}

| Nom | Description |
| --- | --- |
| getDependingSlides () | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître. |

 **Renvoie:**
[Slide](../slide)


---


### getDrawingGuides {#getDrawingGuides}

| Nom | Description |
| --- | --- |
| getDrawingGuides () | Renvoie une collection de guides de dessin pour la diapositive maître. Lecture seule IDrawingGuidesCollection |

 **Renvoie:**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Nom | Description |
| --- | --- |
| getHeaderFooterManager () | Renvoie le gestionnaire d’en-tête et pied de page de la diapositive maître. Lecture seule IMasterSlideHeaderFooterManager. |

 **Renvoie:**
[MasterSlideHeaderFooterManager](../masterslideheaderfootermanager)


---


### getLayoutSlides {#getLayoutSlides}

| Nom | Description |
| --- | --- |
| getLayoutSlides () | Renvoie la collection des diapositives de disposition enfant pour cette diapositive maître. Lecture seule IMasterLayoutSlideCollection. Vous pouvez accéder à l’API alternative pour ajouter/inserer/supprimer/dupliquer des diapositives de disposition en utilisant la propriété ( IPresentation#getLayoutSlides). |

 **Renvoie:**
[MasterLayoutSlideCollection](../masterlayoutslidecollection)


---


### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Renvoie ou définit le nom d’une diapositive maître. Lecture/écriture String. |

 **Renvoie:**
String


---


### getOtherStyle {#getOtherStyle}

| Nom | Description |
| --- | --- |
| getOtherStyle () | Renvoie le style d’un autre texte. Lecture seule ITextStyle. |

 **Renvoie:**
[TextStyle](../textstyle)


---


### getPreserve {#getPreserve}

| Nom | Description |
| --- | --- |
| getPreserve () | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais automatiquement un maître inutilisé ; pour réellement supprimer les maîtres inutilisés, appelez MasterSlideCollection#removeUnused(boolean). Lecture/écriture boolean. |

 **Renvoie:**
boolean


---


### getShowMasterShapes {#getShowMasterShapes}

| Nom | Description |
| --- | --- |
| getShowMasterShapes () | Indique si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean. |

 **Renvoie:**
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Levée si {@code true} est défini pour la diapositive maître. |


---


### getThemeManager {#getThemeManager}

| Nom | Description |
| --- | --- |
| getThemeManager () | Renvoie le gestionnaire de thème. Lecture seule IMasterThemeManager. |

 **Renvoie:**
[MasterThemeManager](../masterthememanager)


---


### getTitleStyle {#getTitleStyle}

| Nom | Description |
| --- | --- |
| getTitleStyle () | Renvoie le style d’un texte de titre. Lecture seule ITextStyle. |

 **Renvoie:**
[TextStyle](../textstyle)


---


### hasDependingSlides {#hasDependingSlides}

| Nom | Description |
| --- | --- |
| hasDependingSlides () | Renvoie true s’il existe au moins une diapositive qui dépend de cette diapositive maître. Lecture seule boolean. |

 **Renvoie:**
boolean


---


### setName {#setName}

| Nom | Description |
| --- | --- |
| setName (String) | Renvoie ou définit le nom d’une diapositive maître. Lecture/écriture String. |

 **Renvoie:**
void


---


### setPreserve {#setPreserve}

| Nom | Description |
| --- | --- |
| setPreserve (boolean) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais automatiquement un maître inutilisé ; pour réellement supprimer les maîtres inutilisés, appelez MasterSlideCollection#removeUnused(boolean). Lecture/écriture boolean. |

 **Renvoie:**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| Nom | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Indique si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean. |

 **Renvoie:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Levée si {@code true} est défini pour la diapositive maître. |


---