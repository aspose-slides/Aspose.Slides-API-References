---
title: IMasterHandoutSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje hlavní snímek pro podklady.
type: docs
url: /cs/com.aspose.slides/imasterhandoutslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Reprezentuje hlavní snímek pro podklady.

## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter pro hlavní snímek podkladů. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek pro hlavní snímek podkladů. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter pro hlavní snímek podkladů. Pouze ke čtení [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Vrací:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslicích vodítek pro hlavní snímek podkladů. Pouze ke čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Přidání nového vodorovného kreslicího vodítka nad střed snímku
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)