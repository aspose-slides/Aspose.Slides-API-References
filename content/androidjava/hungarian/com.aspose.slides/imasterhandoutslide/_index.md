---
title: IMasterHandoutSlide
second_title: Aspose.Slides Androidhoz Java API hivatkozáson keresztül
description: A jegyzetlapok mesterdiáját képviseli.
type: docs
url: /hu/com.aspose.slides/imasterhandoutslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

A jegyzetlapok mesterdiáját képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mesterhandout dia HeaderFooter menedzserét. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a mesterhandout dia rajzsegédeinek gyűjteményét. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mesterhandout dia HeaderFooter menedzserét. Csak olvasható [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszatér:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a mesterhandout dia rajzsegédeinek gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      //      Új vízszintes rajzsegéd hozzáadása a dia középpontja felett
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)