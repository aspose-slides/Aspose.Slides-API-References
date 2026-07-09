---
title: IBaseSlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les données communes pour tous les types de diapositives.
type: docs
url: /fr/com.aspose.slides/ibaseslide/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Représente les données communes pour tous les types de diapositives.
## Méthodes

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Renvoie les formes d'une diapositive. |
| [getControls()](#getControls--) | Renvoie la collection des contrôles ActiveX d'une diapositive. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une diapositive. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une diapositive. |
| [getSlideId()](#getSlideId--) | Renvoie l'ID d'une diapositive. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la diapositive. |
| [getTimeline()](#getTimeline--) | Renvoie l'objet de timeline d'animation. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Renvoie l'objet TransitionEx qui contient des informations sur la façon dont la diapositive spécifiée avance pendant le diaporama. |
| [getBackground()](#getBackground--) | Renvoie l'arrière-plan de la diapositive. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Détermine si les deux instances IBaseSlide sont égales. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Renvoie les formes d'une diapositive. Lecture seule [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Renvoie :**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Renvoie la collection des contrôles ActiveX d'une diapositive. Lecture seule [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Renvoie :**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Renvoie ou définit le nom d'une diapositive. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Renvoie ou définit le nom d'une diapositive. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Renvoie l'ID d'une diapositive. Lecture seule long.

**Renvoie :**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Renvoie les données personnalisées de la diapositive. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie :**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Renvoie l'objet de timeline d'animation. Lecture seule [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Renvoie :**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Renvoie l'objet TransitionEx qui contient des informations sur la façon dont la diapositive spécifiée avance pendant le diaporama. Lecture seule [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Renvoie :**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Renvoie l'arrière-plan de la diapositive. Lecture seule [IBackground](../../com.aspose.slides/ibackground).

**Renvoie :**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fournit un accès facile aux hyperliens contenus. Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Trouve la première occurrence d'une forme avec le texte alternatif spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Texte alternatif. |

**Renvoie :**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Joint les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Détermine si les deux instances IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par ex. SlideId, ni du contenu dynamique, par ex. la valeur de date actuelle dans le Date Placeholder.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | L'IBaseSlide à comparer avec l'IBaseSlide actuel. |

**Renvoie :**
boolean - **true** si l'IBaseSlide spécifié est égal à l'IBaseSlide actuel ; sinon, **false**.