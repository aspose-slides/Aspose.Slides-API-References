---
title: MasterHandoutSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar master-bild för handouts.
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

Representerar master-bild för handouts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanterare för master-handout-bilden. |
| [getThemeManager()](#getThemeManager--) | Returnerar temahanteraren. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling ritningsguider för master-handout-bilden. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Anger om former på master-bilden ska visas på bilder eller inte. För själva master-bilden returnerar denna egenskap alltid false. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Anger om former på master-bilden ska visas på bilder eller inte. För själva master-bilden returnerar denna egenskap alltid false. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returnerar HeaderFooter-hanterare för master-handout-bilden. Skrivskyddad [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

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


Returnerar en samling ritningsguider för master-handout-bilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Lägger till den nya horisontella ritningsguiden ovanför bildens centrum
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)