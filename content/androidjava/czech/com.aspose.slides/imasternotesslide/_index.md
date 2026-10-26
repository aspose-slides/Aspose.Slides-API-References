---
title: IMasterNotesSlide
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje hlavní snímek pro poznámky.
type: docs
url: /cs/com.aspose.slides/imasternotesslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Represents master slide for notes.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku poznámek. |
| [getNotesStyle()](#getNotesStyle--) | Vrací styl textu poznámek. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek pro hlavní snímek poznámek. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter hlavního snímku poznámek. Pouze pro čtení [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Vrací:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

Vrací styl textu poznámek. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslicích vodítek pro hlavní snímek poznámek. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Přidání nového horizontálního kreslicího vodítka pod střed snímku
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)