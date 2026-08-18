---
title: MasterHandoutSlide
second_title: Aspose.Slides Java API referencia
description: A szórólapok mesterdiáját képviseli.
type: docs
url: /hu/com.aspose.slides/masterhandoutslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden implementált interfész:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

A fődia a szórólapokhoz.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdián lévő alakzatok megjelennek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdián lévő alakzatok megjelennek-e a diákon vagy sem. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mester kiosztási dia HeaderFooter kezelőjét. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma kezelőt. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a mester kiosztási dia rajzsegédleteiről. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a mesterdián lévő alakzatok megjelennek-e a diákon vagy sem. A mesterdiára vonatkozóan ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Visszatér:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdián lévő alakzatok megjelennek-e a diákon vagy sem. A mesterdiára vonatkozóan ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mester kiosztási dia HeaderFooter kezelőjét. Csak olvasható [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszatér:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a téma kezelőt. Csak olvasható [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszatér:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a mester kiosztási dia rajzsegédleteiről. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Új vízszintes rajzsegédlet hozzáadása a dia középpontja felett
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)