---
title: IMasterHandoutSlide
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje slajd master dla notatek.
type: docs
url: /pl/com.aspose.slides/imasterhandoutslide/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Reprezentuje slajd master dla notatek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter master slajdu notatek. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla master slajdu notatek. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter master slajdu notatek. Tylko do odczytu [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Zwraca:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Zwraca kolekcję przewodników rysowania dla master slajdu notatek. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Dodawanie nowej poziomej linii rysunkowej powyżej środka slajdu
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)