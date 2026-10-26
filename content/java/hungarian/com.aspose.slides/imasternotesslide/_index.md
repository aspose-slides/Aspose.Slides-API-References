---
title: IMasterNotesSlide
second_title: Aspose.Slides Java API-referenciája
description: A jegyzetek mester diáját képviseli.
type: docs
url: /hu/com.aspose.slides/imasternotesslide/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

A jegyzetek mester diáját képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a master notes slide HeaderFooter kezelőjét. |
| [getNotesStyle()](#getNotesStyle--) | Visszaadja egy jegyzet szöveg stílusát. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a master notes slide rajzolási segédvonalairól. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a master notes slide HeaderFooter kezelőjét. Csak olvasható [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Visszatér:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Visszaadja egy jegyzet szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Visszaad egy gyűjteményt a master notes slide rajzolási segédvonalairól. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Új vízszintes rajzolási segédvonal hozzáadása a dia középpontja alá
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)