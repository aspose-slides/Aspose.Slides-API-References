---
title: LayoutSlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une diapositive de mise en page.
type: docs
url: /fr/com.aspose.slides/layoutslide/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Représente une diapositive de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Renvoie le gestionnaire placeholder de la diapositive de mise en page. |
| [getMasterSlide()](#getMasterSlide--) | Renvoie ou définit la diapositive maîtresse pour une mise en page. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Renvoie ou définit la diapositive maîtresse pour une mise en page. |
| [remove()](#remove--) | Supprime la mise en page de la présentation. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème de remplacement. |
| [getLayoutType()](#getLayoutType--) | Renvoie le type de mise en page de cette diapositive de mise en page. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives dépendant de cette diapositive de mise en page. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie true si au moins une diapositive dépend de cette diapositive de mise en page. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive de mise en page. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Renvoie :**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Renvoie le gestionnaire placeholder de la diapositive de mise en page. Lecture seule [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Renvoie :**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Renvoie ou définit la diapositive maîtresse pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Renvoie :**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Renvoie ou définit la diapositive maîtresse pour une mise en page. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Supprime la mise en page de la présentation.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème de remplacement. Lecture seule [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Renvoie :**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Renvoie :**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Renvoie un tableau contenant toutes les diapositives dépendant de cette diapositive de mise en page.

**Renvoie :**
com.aspose.slides.ISlide[] - Tableau de [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Renvoie true si au moins une diapositive dépend de cette diapositive de mise en page. Lecture seule  boolean .

**Renvoie :**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Lecture/écriture  boolean .

**Renvoie :**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive de mise en page. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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

**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)