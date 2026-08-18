---
title: IMasterHandoutSlide
second_title: Aspose.Slides Java API referencia
description: A kézikönyvekhez használt mesterdia.
type: docs
url: /hu/com.aspose.slides/imasterhandoutslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

A kézikönyv mesterdia diát jelöli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mesterkézikönyv dia HeaderFooter kezelőjét. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a mesterkézikönyv dia rajzolási segédvonalakról. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mesterkézikönyv dia HeaderFooter kezelőjét. Csak olvasható [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszatér:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a mesterkézikönyv dia rajzolási segédvonalakról. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Az új vízszintes rajzsegédvonal hozzáadása a dia középpontja fölé
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)