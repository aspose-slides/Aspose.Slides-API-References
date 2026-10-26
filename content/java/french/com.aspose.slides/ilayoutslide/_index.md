---
title: ILayoutSlide
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Renvoie le gestionnaire de placeholder de la diapositive de mise en page. |
| [getMasterSlide()](#getMasterSlide--) | Renvoie ou définit le master slide pour une mise en page. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Renvoie ou définit le master slide pour une mise en page. |
| [getLayoutType()](#getLayoutType--) | Renvoie le type de mise en page de cette diapositive de mise en page. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page. |
| [remove()](#remove--) | Supprime la mise en page de la présentation. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive de mise en page. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Renvoie :**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Renvoie le gestionnaire de placeholder de la diapositive de mise en page. Lecture seule [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Renvoie :**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Renvoie ou définit le master slide pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Renvoie :**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Renvoie ou définit le master slide pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Renvoie :**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page. Lecture seule booléen.

**Renvoie :**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page.

**Renvoie :**
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

Renvoie une collection de guides de dessin pour la diapositive de mise en page. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Ajout du nouveau guide de dessin vertical à gauche du centre de la diapositive
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)