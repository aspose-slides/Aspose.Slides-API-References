---
title: ILayoutSlide
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente une diapositive de mise en page.
type: docs
url: /fr/com.aspose.slides/ilayoutslide/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Représente une diapositive de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourne le gestionnaire HeaderFooter de la diapositive de mise en page. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retourne le gestionnaire d'espace réservé de la diapositive de mise en page. |
| [getMasterSlide()](#getMasterSlide--) | Retourne ou définit la diapositive maître pour une mise en page. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retourne ou définit la diapositive maître pour une mise en page. |
| [getLayoutType()](#getLayoutType--) | Retourne le type de mise en page de cette diapositive de mise en page. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourne vrai s'il existe au moins une diapositive dépendant de cette diapositive de mise en page. |
| [getDependingSlides()](#getDependingSlides--) | Retourne un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page. |
| [remove()](#remove--) | Supprime la mise en page de la présentation. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourne une collection de guides de dessin pour la diapositive de mise en page. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourne le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retourne :**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Retourne le gestionnaire d'espace réservé de la diapositive de mise en page. Lecture seule [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retourne :**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Retourne ou définit la diapositive maître pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retourne :**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Retourne ou définit la diapositive maître pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Retourne le type de mise en page de cette diapositive de mise en page. Lecture seule [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retourne :**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Retourne vrai s'il existe au moins une diapositive dépendant de cette diapositive de mise en page. Lecture seule boolean.

**Retourne :**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Retourne un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page.

**Retourne :**
com.aspose.slides.ISlide[] - Tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page
### remove() {#remove--}
```
public abstract void remove()
```


Supprime la mise en page de la présentation.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retourne une collection de guides de dessin pour la diapositive de mise en page. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the left of the slide center
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)