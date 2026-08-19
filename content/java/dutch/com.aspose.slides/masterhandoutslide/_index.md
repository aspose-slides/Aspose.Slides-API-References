---
title: MasterHandoutSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de masterslide voor hand-outs voor.
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

Stelt de masterslide voor hand-outs voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterslide op dia's getoond moeten worden of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterslide op dia's getoond moeten worden of niet. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter manager van de master handout slide. |
| [getThemeManager()](#getThemeManager--) | Retourneert de theme manager. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie van drawing guides voor de master handout slide. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificeert of vormen op de masterslide op dia's getoond moeten worden of niet. Voor de masterslide zelf geeft deze eigenschap altijd false terug. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificeert of vormen op de masterslide op dia's getoond moeten worden of niet. Voor de masterslide zelf geeft deze eigenschap altijd false terug. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter manager van de master handout slide. Alleen-lezen [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retourneert:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Retourneert de theme manager. Alleen-lezen [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourneert:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een collectie van drawing guides voor de master handout slide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Toevoegen van de nieuwe horizontale tekenhulp boven het midden van de dia
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)