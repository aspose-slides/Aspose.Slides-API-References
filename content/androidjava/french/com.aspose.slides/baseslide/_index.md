---
title: BaseSlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les données communes à tous les types de diapositive.
type: docs
url: /fr/com.aspose.slides/baseslide/
---
**Inheritance:**  
java.lang.Object

**Toutes les interfaces implémentées :**  
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
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les fragments avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Fusionne les fragments avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie un thème effectif pour cette diapositive. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la diapositive. |
| [getTimeline()](#getTimeline--) | Renvoie l’objet de chronologie d’animation. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Renvoie l’objet Transition qui contient des informations sur la façon dont la diapositive spécifiée progresse pendant un diaporama. |
| [getBackground()](#getBackground--) | Renvoie l’arrière-plan de la diapositive. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Trouve la première occurrence d’une forme avec le texte alternatif spécifié. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Renvoie l’interface IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Renvoie les formes d’une diapositive. Lecture-seule [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Renvoie :**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Renvoie la collection de contrôles ActiveX d’une diapositive. Lecture-seule [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Renvoie :**  
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public String getName()
```

Renvoie ou définit le nom d’une diapositive. Lecture-écriture String.

**Renvoie :**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Renvoie ou définit le nom d’une diapositive. Lecture-écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Renvoie l’ID d’une diapositive. Lecture-seule long.

**Renvoie :**  
long

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Détermine si les deux instances IBaseSlide sont égales. La valeur de retour est calculée à partir de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d’identifiants uniques, par ex. SlideId, ni du contenu dynamique, par ex. la valeur de date actuelle dans le texte de substitution.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Returns:**
boolean -  **true**  if the specified IBaseSlide is equal to the current IBaseSlide; otherwise,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Joins runs with same formatting in all paragraphs all acceptable shapes.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Joins runs with same formatting in all paragraphs in all acceptable shapes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Returns an effective theme for this slide.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Returns the slide's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Returns animation timeline object. Read-only [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Returns slide's background. Read-only [IBackground](../../com.aspose.slides/ibackground).

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Provides easy access to contained hyperlinks. Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture booléen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Finds first occurrence of a shape with the specified alternative text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternative text. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape object or null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture-seule IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns IPresentation interface. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()


Renvoie la diapositive de base. Lecture-seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie :**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)