---
title: IMasterHandoutSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar masterbild för handouts.
type: docs
url: /sv/com.aspose.slides/imasterhandoutslide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Representerar masterbild för handouts.
## Metoder

| Method | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för master handout-bilden. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling ritguider för master handout-bilden. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returnerar HeaderFooter manager för master handout-bilden. Skrivskyddad [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Returnerar:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Returnerar en samling ritguider för master handout-bilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Lägger till den nya horisontella ritguiden ovanför bildens centrum
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)