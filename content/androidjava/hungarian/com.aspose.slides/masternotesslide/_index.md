---
title: MasterNotesSlide
second_title: Aspose.Slides Android Java API hivatkozás
description: A jegyzetek mesterdiáját képviseli.
type: docs
url: /hu/com.aspose.slides/masternotesslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

A jegyzetek mesterdiáját képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mester jegyzetdiák HeaderFooter kezelőjét. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma kezelőjét. |
| [getNotesStyle()](#getNotesStyle--) | Visszaadja a jegyzet szöveg stílusát. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a mesterjegyzet-diához tartozó rajzsegédletekről. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Visszatér:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mesterjegyzet-diához tartozó HeaderFooter kezelőt. Csak olvasás [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszatér:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a téma kezelőt. Csak olvasás [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszatér:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Visszaadja a jegyzet szöveg stílusát. Csak olvasás [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a mesterjegyzet-diához tartozó rajzsegédletekről. Csak olvasás [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Új vízszintes rajzsegédlet hozzáadása a dia közepének alá
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)