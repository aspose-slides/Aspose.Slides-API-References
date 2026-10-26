---
title: MasterNotesSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar mastersida för anteckningar.
type: docs
url: /sv/com.aspose.slides/masternotesslide/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Representerar master-bilden för anteckningar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för master-antecknings-bilden. |
| [getThemeManager()](#getThemeManager--) | Returnerar temahanteraren. |
| [getNotesStyle()](#getNotesStyle--) | Returnerar stilen för en anteckningstext. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritguider för master-antecknings-bilden. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Anger om former på master-bilden ska visas på bilder eller inte. För master-bilden själv returnerar denna egenskap alltid false. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Anger om former på master-bilden ska visas på bilder eller inte. För master-bilden själv returnerar denna egenskap alltid false. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för master-antecknings-bilden. Skrivskyddad [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Returnerar:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Returnerar temahanteraren. Skrivskyddad [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Returnerar:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Returnerar stilen för en anteckningstext. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling av ritguider för master-antecknings-bilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Lägger till den nya horisontella ritguiden under bildens centrum
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)