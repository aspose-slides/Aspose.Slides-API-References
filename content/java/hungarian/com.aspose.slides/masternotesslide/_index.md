---
title: MasterNotesSlide
second_title: Aspose.Slides Java API Referencia
description: A jegyzetek fődiapozitívját képviseli.
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

A jegyzetek fődiapozitívját képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a fődiapozitívon lévő alakzatok meg legyenek jelenítve a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a fődiapozitívon lévő alakzatok meg legyenek jelenítve a diákon vagy sem. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a főjegyzetdiapozitív HeaderFooter kezelőjét. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma kezelőjét. |
| [getNotesStyle()](#getNotesStyle--) | Visszaadja a jegyzet szöveg stílusát. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a főjegyzetdiapozitív rajzsegélyek gyűjteményét. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a fődiapozitívon lévő alakzatok meg legyenek jelenítve a diákon vagy sem. A fődiapozitív esetén ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a fődiapozitívon lévő alakzatok meg legyenek jelenítve a diákon vagy sem. A fődiapozitív esetén ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a főjegyzetdiapozitív HeaderFooter kezelőjét. Csak olvasható [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszatérési érték:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a téma kezelőjét. Csak olvasható [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszatérési érték:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Visszaadja egy jegyzet szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a főjegyzetdiapozitív rajzsegélyek gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Új vízszintes rajzsegély hozzáadása a diapozitív középpont alá
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)