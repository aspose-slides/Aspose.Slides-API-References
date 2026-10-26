---
title: IMasterHandoutSlide
second_title: Aspose.Slides pro Java API Reference
description: Představuje hlavní snímek pro letáky.
type: docs
url: /cs/com.aspose.slides/imasterhandoutslide/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Představuje hlavní snímek pro letáky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku pro letáky. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci výkresových vodítek pro hlavní snímek pro letáky. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Vrací správce HeaderFooter hlavního snímku pro letáky. Pouze ke čtení [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Vrací:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Vrací kolekci výkresových vodítek pro hlavní snímek pro letáky. Pouze ke čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Přidání nového vodorovného kreslicího vodidla nad střed snímku
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)