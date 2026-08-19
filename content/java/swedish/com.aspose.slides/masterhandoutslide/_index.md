---
title: MasterHandoutSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar mastersliden för handouts.
type: docs
url: /sv/com.aspose.slides/masterhandoutslide/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Representerar mastersliden för handouts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på mastersliden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på mastersliden ska visas på bilder eller inte. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för master-handout-sliden. |
| [getThemeManager()](#getThemeManager--) | Returnerar temahanteraren. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritningsguider för master-handout-sliden. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Anger om former på mastersliden ska visas på bilder eller inte. För själva mastersliden returnerar denna egenskap alltid false. Läs/skriv boolesk.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Anger om former på mastersliden ska visas på bilder eller inte. För själva mastersliden returnerar denna egenskap alltid false. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter manager för master-handout-sliden. Skrivskyddad [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Returnerar:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Returnerar temahanteraren. Skrivskyddad [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Returnerar:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling av ritningsguider för master-handout-sliden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Lägger till den nya horisontella ritningsguiden ovanför slidens centrum
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)