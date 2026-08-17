---
title: BaseSlide
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les données communes à tous les types de diapositives.
type: docs
url: /fr/com.aspose.slides/baseslide/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Représente les données communes à tous les types de diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Renvoie les formes d’une diapositive. |
| [getControls()](#getControls--) | Renvoie la collection de contrôles ActiveX d’une diapositive. |
| [getName()](#getName--) | Renvoie ou définit le nom d’une diapositive. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d’une diapositive. |
| [getSlideId()](#getSlideId--) | Renvoie l’ID d’une diapositive. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Détermine si les deux instances IBaseSlide sont égales. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie un thème effectif pour cette diapositive. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la diapositive. |
| [getTimeline()](#getTimeline--) | Renvoie l’objet de la ligne temporelle d’animation. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Renvoie l’objet Transition qui contient les informations sur la façon dont la diapositive spécifiée progresse pendant un diaporama. |
| [getBackground()](#getBackground--) | Renvoie l’arrière-plan de la diapositive. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Trouve la première occurrence d’une forme avec le texte alternatif spécifié. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Renvoie l’interface IPresentation. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Renvoie les formes d’une diapositive. Lecture seule [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Renvoie:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Renvoie la collection de contrôles ActiveX d’une diapositive. Lecture seule [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Renvoie:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


Renvoie ou définit le nom d’une diapositive. Lecture/écriture String.

**Renvoie:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Renvoie ou définit le nom d’une diapositive. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Renvoie l’ID d’une diapositive. Lecture seule long.

**Renvoie:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Détermine si les deux instances IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et de son contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d’identifiants uniques, par ex. SlideId, ni du contenu dynamique, par ex. la valeur de date actuelle dans un espace réservé de date.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuel. |

**Renvoie:**
boolean -  **true**  si l’IBaseSlide spécifié est égal à l’IBaseSlide actuel ; sinon,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Renvoie un thème effectif pour cette diapositive.

**Renvoie:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Renvoie les données personnalisées de la diapositive. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Renvoie l’objet de la ligne temporelle d’animation. Lecture seule [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Renvoie:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Renvoie l’objet Transition qui contient les informations sur la façon dont la diapositive spécifiée progresse pendant un diaporama. Lecture seule [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Renvoie:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Renvoie l’arrière-plan de la diapositive. Lecture seule [IBackground](../../com.aspose.slides/ibackground).

**Renvoie:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Fournit un accès facile aux hyperliens contenus. Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Renvoie:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Trouve la première occurrence d’une forme avec le texte alternatif spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Texte alternatif. |

**Renvoie:**
[IShape](../../com.aspose.slides/ishape) - objet Shape ou null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie l’interface IPresentation. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)