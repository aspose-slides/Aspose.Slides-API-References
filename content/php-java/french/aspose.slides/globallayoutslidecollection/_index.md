---
title: GlobalLayoutSlideCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection classe

Représente une collection de toutes les diapositives de mise en page dans la présentation.  
Étend la classe LayoutSlideCollection avec des méthodes pour ajouter/dupliquer les diapositives de mise en page dans le contexte de l'union des collections individuelles des diapositives de mise en page du maître.

### add {#add}

| Nom | Description |
| --- | --- |
| add ([MasterSlide](../masterslide), byte, String) | Ajoute une nouvelle diapositive de mise en page à la présentation. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| master | [MasterSlide](../masterslide) | Diapositive maître pour une nouvelle mise en page. |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. D’autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est nul, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1_Title Slide », « 2_.. », etc.). 1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom de layoutType ne contient aucun espace réservé ni aucune forme. 2) L'analogue de cette méthode est la méthode IMasterLayoutSlideCollection#add(byte,String) accessible via la propriété ( IMasterSlide#getLayoutSlides). |

**Retour :**  
[LayoutSlide](../layoutslide)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Levée si la valeur du nom de mise en page layoutName est déjà utilisée dans la collection des mises en page du maître. |

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Diapositive à cloner. Lors du clonage d'une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné afin de conserver le formatage source. Un registre interne est utilisé pour suivre automatiquement les maîtres clonés afin d'éviter la création de multiples clones du même maître de diapositive. Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré. |

**Retour :**  
[LayoutSlide](../layoutslide)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide), [MasterSlide](../masterslide)) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Diapositive à cloner. |
| destMaster | [MasterSlide](../masterslide) | Diapositive maîtresse pour une nouvelle mise en page. 1) La nouvelle mise en page sera liée au maître défini dans la présentation de destination. Il s'agit donc de l'analogue de copier/coller avec l'option « Utiliser le thème de destination » dans PowerPoint. 2) L'analogue de cette méthode est la méthode IMasterLayoutSlideCollection#addClone(ILayoutSlide) accessible via la propriété ( IMasterSlide#getLayoutSlides). |

**Retour :**  
[LayoutSlide](../layoutslide)

---