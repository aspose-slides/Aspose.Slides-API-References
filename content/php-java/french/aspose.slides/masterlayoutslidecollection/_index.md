---
title: MasterLayoutSlideCollection
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/masterlayoutslidecollection/
---
## classe MasterLayoutSlideCollection

 Représente une collection de toutes les diapositives de mise en page d’une diapositive maîtresse définie.  
 Étend la classe LayoutSlideCollection avec des méthodes pour ajouter/inserer/supprimer/dupliquer/reordonner les diapositives de mise en page dans le contexte des collections individuelles des diapositives de mise en page du maître.

### add {#add}

| Nom | Description |
| --- | --- |
| add (byte, String) | Ajoute une nouvelle diapositive de mise en page à la fin de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. D’autres types de mise en page ne sont pas pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est null, le nom est généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1_Title Slide », « 2_.. », etc.). 1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom du layoutType ne contient aucun espace réservé et aucune forme. 2) L’analogue de cette méthode est la méthode IGlobalLayoutSlideCollection#add(IMasterSlide,byte,String) accessible via la propriété ( IPresentation#getLayoutSlides). |

**Renvoie :**  
[LayoutSlide](../layoutslide)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Levée si la valeur du nom de mise en page layoutName est déjà utilisée dans cette collection de mises en page. |

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | Ajoute une copie d’une diapositive de mise en page spécifiée à la fin de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Diapositive à dupliquer. 1) La nouvelle mise en page sera liée à la diapositive maître parente pour cette collection de diapositives de mise en page. Il s’agit donc d’un analogue de copier/coller avec l’option « Use Destination Theme » dans PowerPoint. 2) L’analogue de cette méthode est la méthode IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) accessible via la propriété ( IPresentation#getLayoutSlides). |

**Renvoie :**  
[LayoutSlide](../layoutslide)

---

### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, byte, String) | Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de la nouvelle diapositive. |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. D’autres types de mise en page ne sont pas pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est null, le nom est généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1_Title Slide », « 2_.. », etc.). La mise en page insérée pour la valeur SlideLayoutType.Custom du layoutType ne contient aucun espace réservé et aucune forme. |

**Renvoie :**  
[LayoutSlide](../layoutslide)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Levée si la valeur du nom de mise en page layoutName est déjà utilisée dans cette collection de mises en page. |

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [LayoutSlide](../layoutslide)) | Insère une copie d’une diapositive de mise en page spécifiée à la position indiquée de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de la nouvelle diapositive. |
| sourceLayout | [LayoutSlide](../layoutslide) | Diapositive à dupliquer. La nouvelle mise en page sera liée à la diapositive maître parente pour cette collection de diapositives de mise en page. |

**Renvoie :**  
[LayoutSlide](../layoutslide)

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l’élément à l’indice spécifié de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de l’élément à supprimer. 1) Pour éviter le déclenchement de l’exception PptxEditException, vérifier la propriété HasDependingSlides de la mise en page au préalable. 2) Vous pouvez également utiliser la méthode ILayoutSlide#remove pour simplifier le code. |

**Renvoie :**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Levée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

---

### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [LayoutSlide](../layoutslide)) | Déplace la diapositive de mise en page de la collection vers la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice cible. |
| layoutSlide | [LayoutSlide](../layoutslide) | Diapositive à déplacer. |

**Renvoie :**  
void