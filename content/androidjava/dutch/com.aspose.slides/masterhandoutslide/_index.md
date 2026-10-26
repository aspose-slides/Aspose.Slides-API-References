---
title: MasterHandoutSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de masterslide voor hand-outs.
type: docs
url: /nl/com.aspose.slides/masterhandoutslide/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Stelt de masterslide voor voor hand-outs.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterslide al dan niet op de dia's worden weergegeven. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterslide al dan niet op de dia's worden weergegeven. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-beheerder van de master-handoutslide. |
| [getThemeManager()](#getThemeManager--) | Retourneert de themabeheerder. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie tekengidsen voor de master-handoutslide. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificeert of vormen op de masterslide al dan niet op de dia's worden weergegeven. Voor de masterslide zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificeert of vormen op de masterslide al dan niet op de dia's worden weergegeven. Voor de masterslide zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert de HeaderFooter-beheerder van de master-handoutslide. Alleen-lezen [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retourneert:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Retourneert de themabeheerder. Alleen-lezen [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourneert:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een collectie tekengidsen voor de master-handoutslide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Voegt de nieuwe horizontale tekengids toe boven het midden van de dia
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)