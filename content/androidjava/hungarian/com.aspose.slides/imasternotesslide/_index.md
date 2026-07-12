---
title: IMasterNotesSlide
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: A jegyzetek mesterdiapozitívját képviseli.
type: docs
url: /hu/com.aspose.slides/imasternotesslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

A jegyzetek mesterdiapozitívját képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszatér a HeaderFooter menedzserrel a jegyzetek mesterdiapozitívjához. |
| [getNotesStyle()](#getNotesStyle--) | Visszatér a jegyzet szövegének stílusával. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszatér a mesterjegyzet-diapozitív rajzsegédletek gyűjteményével. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Visszatér a HeaderFooter menedzserrel a mesterjegyzet-diapozitívhoz. Csak olvasható [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Visszatér:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

Visszatér a jegyzet szövegének stílusával. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszatér a mesterjegyzet-diapozitívhoz tartozó rajzsegédletek gyűjteményével. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Új vízszintes rajzsegédlet hozzáadása a dia középpontja alá
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)