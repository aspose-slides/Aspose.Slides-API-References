---
title: IMasterNotesSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de master slide voor notities voor.
type: docs
url: /nl/com.aspose.slides/imasternotesslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Stelt de master slide voor notities voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter beheerder van de master notitieslide. |
| [getNotesStyle()](#getNotesStyle--) | Retourneert de stijl van een notitietekst. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een verzameling tekengidsen voor de master notitieslide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter beheerder van de master notitieslide. Alleen-lezen [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Retourneert:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Retourneert de stijl van een notitietekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een verzameling tekengidsen voor de master notitieslide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // De nieuwe horizontale tekengids toevoegen onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)