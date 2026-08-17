---
title: LayoutSlide
second_title: Référence de l'API Aspose.Slides for Java
description: Représente une diapositive de disposition.
type: docs
url: /fr/com.aspose.slides/layoutslide/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Représente une diapositive de disposition.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive de disposition. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Renvoie le gestionnaire de placeholder de la diapositive de disposition. |
| [getMasterSlide()](#getMasterSlide--) | Renvoie ou définit la diapositive maître pour une disposition. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Renvoie ou définit la diapositive maître pour une disposition. |
| [remove()](#remove--) | Supprime la disposition de la présentation. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème de substitution. |
| [getLayoutType()](#getLayoutType--) | Renvoie le type de disposition de cette diapositive de disposition. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de disposition. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie true s'il existe au moins une diapositive qui dépend de cette diapositive de disposition. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive de disposition. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive de disposition. Lecture seule [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Renvoie:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Renvoie le gestionnaire de placeholder de la diapositive de disposition. Lecture seule [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Renvoie:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Renvoie ou définit la diapositive maître pour une disposition. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Renvoie:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Renvoie ou définit la diapositive maître pour une disposition. Lecture/écriture [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Supprime la disposition de la présentation.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème de substitution. Lecture seule [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Renvoie:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Renvoie le type de disposition de cette diapositive de disposition. Lecture seule [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Renvoie:**  
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de disposition.

**Renvoie:**  
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Renvoie true s'il existe au moins une diapositive qui dépend de cette diapositive de disposition. Lecture seule  boolean .

**Renvoie:**  
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture  boolean .

**Renvoie:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture  boolean .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive de disposition. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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


**Renvoie:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)