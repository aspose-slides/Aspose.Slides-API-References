---
title: LayoutSlide
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/layoutslide/
---
## LayoutSlide classe

 Représente une diapositive de mise en page.
 
### getDependingSlides {#getDependingSlides}

| Nom | Description |
| --- | --- |
| getDependingSlides () | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page. |

 **Retourne:**  
[Slide](../slide)


---


### getDrawingGuides {#getDrawingGuides}

| Nom | Description |
| --- | --- |
| getDrawingGuides () | Renvoie une collection de guides de dessin pour la diapositive de mise en page. Lecture seule IDrawingGuidesCollection |

 **Retourne:**  
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Nom | Description |
| --- | --- |
| getHeaderFooterManager () | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule ILayoutSlideHeaderFooterManager. |

 **Retourne:**  
[LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager)


---


### getLayoutType {#getLayoutType}

| Nom | Description |
| --- | --- |
| getLayoutType () | Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule SlideLayoutType. |

 **Retourne:**  
byte


---


### getMasterSlide {#getMasterSlide}

| Nom | Description |
| --- | --- |
| getMasterSlide () | Renvoie ou définit la diapositive principale pour une mise en page. Lecture/écriture IMasterSlide. |

 **Retourne:**  
[MasterSlide](../masterslide)


---


### getPlaceholderManager {#getPlaceholderManager}

| Nom | Description |
| --- | --- |
| getPlaceholderManager () | Renvoie le gestionnaire d'espace réservé de la diapositive de mise en page. Lecture seule ILayoutPlaceholderManager. |

 **Retourne:**  
[LayoutPlaceholderManager](../layoutplaceholdermanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| Nom | Description |
| --- | --- |
| getShowMasterShapes () | Spécifie si les formes de la diapositive principale doivent être affichées sur les diapositives ou non. Lecture/écriture boolean. |

 **Retourne:**  
boolean


---


### getThemeManager {#getThemeManager}

| Nom | Description |
| --- | --- |
| getThemeManager () | Renvoie le gestionnaire de thème de remplacement. Lecture seule IOverrideThemeManager. |

 **Retourne:**  
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)


---


### hasDependingSlides {#hasDependingSlides}

| Nom | Description |
| --- | --- |
| hasDependingSlides () | Renvoie true si au moins une diapositive dépend de cette diapositive de mise en page. Lecture seule booléen. |

 **Retourne:**  
boolean


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove () | Supprime la mise en page de la présentation. |

 **Retourne:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancée si la mise en page a déjà été supprimée de la présentation ou si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est true). Pour éviter le lancement de l'exception PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable. |


---


### setMasterSlide {#setMasterSlide}

| Nom | Description |
| --- | --- |
| setMasterSlide ([MasterSlide](../masterslide)) | Renvoie ou définit la diapositive principale pour une mise en page. Lecture/écriture IMasterSlide. |

 **Retourne:**  
void


---


### setShowMasterShapes {#setShowMasterShapes}

| Nom | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Spécifie si les formes de la diapositive principale doivent être affichées sur les diapositives ou non. Lecture/écriture boolean. |

 **Retourne:**  
void


---