---
title: ForEach_
second_title: Référence de l'API Aspose.Slides pour PHP via Java
description: 
type: docs

url: /fr/aspose.slides/foreach_/
---
## ForEach_ classe

 Représente un groupe de méthodes destinées à itérer sur différents  Presentation objets du modèle.
 Ces méthodes peuvent être utiles si vous devez itérer et modifier le formatage ou le contenu de certains éléments de Presentation,
  par exemple, modifier le formatage de chaque portion. 

### ForEach_ {#ForEach_}

| Nom | Description |
| --- | --- |
| ForEach_() |  |

 **Retour :**
ForEach_


---


### layoutSlide {#layoutSlide}

| Nom | Description |
| --- | --- |
| layoutSlide ([Presentation](../presentation), [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback)) | Itérer chaque #layoutSlide(Presentation,ForEachLayoutSlideCallback) dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les diapositives de mise en page |
| forEachLayoutSlide | [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback) | Callback qui sera invoqué pour chaque diapositive de mise en page |

 **Retour :**
void


---


### masterSlide {#masterSlide}

| Nom | Description |
| --- | --- |
| masterSlide ([Presentation](../presentation), [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback)) | Itérer chaque #masterSlide(Presentation,ForEachMasterSlideCallback) dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les diapositives maîtres |
| forEachMasterSlide | [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback) | Callback qui sera invoqué pour chaque diapositive maître |

 **Retour :**
void


---


### paragraph {#paragraph}

| Nom | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Itérer chaque Paragraph dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les paragraphes |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback qui sera invoqué pour chaque paragraphe. Les Shapes seront itérés dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) et #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **Retour :**
void


---


### paragraph {#paragraph}

| Nom | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), boolean, [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Itérer chaque Paragraph dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les paragraphes |
| includeNotes | boolean | Indicateur qui indique si les NotesSlides doivent être incluses dans le traitement. |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback qui sera invoqué pour chaque paragraphe. Les Shapes seront itérés dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) et NotesSlide |

 **Retour :**
void


---


### portion {#portion}

| Nom | Description |
| --- | --- |
| portion ([Presentation](../presentation), [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Itérer chaque Portion dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les portions |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback qui sera invoqué pour chaque portion. Les Portions seront itérées dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) et #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **Retour :**
void


---


### portion {#portion}

| Nom | Description |
| --- | --- |
| portion ([Presentation](../presentation), boolean, [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Itérer chaque Portion dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les portions |
| includeNotes | boolean | Indicateur qui indique si les NotesSlides doivent être incluses dans le traitement. |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback qui sera invoqué pour chaque portion. Les Portions seront itérées dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) et NotesSlide |

 **Retour :**
void


---


### shape {#shape}

| Nom | Description |
| --- | --- |
| shape ([Presentation](../presentation), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Itérer chaque Shape dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les shapes de mise en page |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback qui sera invoqué pour chaque shape. Les shapes seront itérés dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) et #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **Retour :**
void


---


### shape {#shape}

| Nom | Description |
| --- | --- |
| shape ([Presentation](../presentation), boolean, [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Itérer chaque Shape dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les shapes de mise en page |
| includeNotes | boolean | Indicateur qui indique si les NotesSlides doivent être incluses dans le traitement. |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback qui sera invoqué pour chaque shape. Les shapes seront itérés dans tous les types de diapositives - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) et NotesSlide si nécessaire. |

 **Retour :**
void


---


### shape {#shape}

| Nom | Description |
| --- | --- |
| shape ([BaseSlide](../baseslide), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Itérer chaque Shape dans la BaseSlide. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide](../baseslide) | Slide pour itérer les shapes de mise en page |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback qui sera invoqué pour chaque shape. BaseSlide est le type de base pour #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) et #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **Retour :**
void


---


### slide {#slide}

| Nom | Description |
| --- | --- |
| slide ([Presentation](../presentation), [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback)) | Itérer chaque #slide(Presentation,ForEachSlideCallback) dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation pour itérer les diapositives |
| forEachSlide | [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback) | Callback qui sera invoqué pour chaque slide |

 **Retour :**
void


---