---
title: IMasterNotesSlide
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt die Masterfolie für Notizen dar.
type: docs
url: /de/com.aspose.slides/imasternotesslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Stellt die Masterfolie für Notizen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Master-Notizfolie zurück. |
| [getNotesStyle()](#getNotesStyle--) | Gibt den Stil eines Notiztextes zurück. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Master-Notizfolie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Master-Notizfolie zurück. Nur lesbar [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Rückgabe:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

Gibt den Stil eines Notiztextes zurück. Nur lesbar [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenhilfen für die Master-Notizfolie zurück. Nur lesbar [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Hinzufügen der neuen horizontalen Zeichenhilfe unterhalb der Folienmitte
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)