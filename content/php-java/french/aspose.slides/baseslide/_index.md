---
title: BaseSlide
second_title: Référence API Java pour Aspose.Sildes en PHP
description: 
type: docs

url: /fr/aspose.slides/baseslide/
---
## BaseSlide classe

  Représente les données communes à tous les types de diapositive.
 
### createThemeEffective {#createThemeEffective}

| Nom | Description |
| --- | --- |
| createThemeEffective () | Renvoie un thème effectif pour cette diapositive. |

 **Renvoie :**
ThemeEffectiveData


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([MasterHandoutSlide](../masterhandoutslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [MasterHandoutSlide](../masterhandoutslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([BaseSlide](../baseslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [BaseSlide](../baseslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([LayoutSlide](../layoutslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [LayoutSlide](../layoutslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([Slide](../slide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([MasterSlide](../masterslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([NotesSlide](../notesslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([MasterNotesSlide](../masternotesslide)) | Détermine si les deux instances de IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [MasterNotesSlide](../masternotesslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuelle. |

 **Renvoie :**
boolean


---


### findShapeByAltText {#findShapeByAltText}

| Nom | Description |
| --- | --- |
| findShapeByAltText (String) | Recherche la première occurrence d'une forme avec le texte alternatif spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| altText | String | Texte alternatif. |

 **Renvoie :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getBackground {#getBackground}

| Nom | Description |
| --- | --- |
| getBackground () | Renvoie l'arrière-plan de la diapositive. Lecture seule IBackground. |

 **Renvoie :**
[Background](../background)


---


### getControls {#getControls}

| Nom | Description |
| --- | --- |
| getControls () | Renvoie la collection de contrôles ActiveX d’une diapositive. Lecture seule IControlCollection. |

 **Renvoie :**
[ControlCollection](../controlcollection)


---


### getCustomData {#getCustomData}

| Nom | Description |
| --- | --- |
| getCustomData () | Renvoie les données personnalisées de la diapositive. Lecture seule ICustomData. |

 **Renvoie :**
[CustomData](../customdata)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Nom | Description |
| --- | --- |
| getHyperlinkQueries () | Fournit un accès facile aux hyperliens contenus. Lecture seule IHyperlinkQueries. |

 **Renvoie :**
[HyperlinkQueries](../hyperlinkqueries)


---


### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Renvoie ou définit le nom d’une diapositive. Lecture/écriture String. |

 **Renvoie :**
String


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie l’interface IPresentation. Lecture seule IPresentation. |

 **Renvoie :**
[Presentation](../presentation)


---


### getShapes {#getShapes}

| Nom | Description |
| --- | --- |
| getShapes () | Renvoie les formes d’une diapositive. Lecture seule IShapeCollection. |

 **Renvoie :**
[ShapeCollection](../shapecollection)


---


### getShowMasterShapes {#getShowMasterShapes}

| Nom | Description |
| --- | --- |
| getShowMasterShapes () | Indique si les formes du masque de diapositive doivent être affichées sur les diapositives ou non. Pour le masque lui-même, cette propriété renvoie toujours false. Lecture/écriture boolean. |

 **Renvoie :**
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Levée si la valeur true est affectée au masque de diapositive. |


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () |  |

 **Renvoie :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideId {#getSlideId}

| Nom | Description |
| --- | --- |
| getSlideId () | Renvoie l’ID d’une diapositive. Lecture seule long. |

 **Renvoie :**
long


---


### getSlideShowTransition {#getSlideShowTransition}

| Nom | Description |
| --- | --- |
| getSlideShowTransition () | Renvoie l’objet Transition qui contient les informations sur la façon dont la diapositive spécifiée progresse pendant le diaporama. Lecture seule ISlideShowTransition. |

 **Renvoie :**
[SlideShowTransition](../slideshowtransition)


---


### getTimeline {#getTimeline}

| Nom | Description |
| --- | --- |
| getTimeline () | Renvoie l’objet de timeline d’animation. Lecture seule IAnimationTimeLine. |

 **Renvoie :**
[AnimationTimeLine](../animationtimeline)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Nom | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Regroupe les portions avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |

 **Renvoie :**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Nom | Description |
| --- | --- |
| joinPortionsWithSameFormatting ([ShapeCollection](../shapecollection)) | Regroupe les portions avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |

 **Renvoie :**
void


---


### setName {#setName}

| Nom | Description |
| --- | --- |
| setName (String) | Définit ou renvoie le nom d’une diapositive. Lecture/écriture String. |

 **Renvoie :**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| Nom | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Indique si les formes du masque de diapositive doivent être affichées sur les diapositives ou non. Pour le masque lui-même, cette propriété renvoie toujours false. Lecture/écriture boolean. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | NotSupportedException | Levée si la valeur true est affectée au masque de diapositive. |


---