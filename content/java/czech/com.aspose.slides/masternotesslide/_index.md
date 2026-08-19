---
title: MasterNotesSlide
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje hlavní snímek pro poznámky.
type: docs
url: /cs/com.aspose.slides/masternotesslide/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Reprezentuje hlavní snímek pro poznámky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifikuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifikuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku s poznámkami. |
| [getThemeManager()](#getThemeManager--) | Vrací správce motivu. |
| [getNotesStyle()](#getNotesStyle--) | Vrací styl textu poznámek. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek pro hlavní snímek s poznámkami. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifikuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifikuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter hlavního snímku s poznámkami. Pouze ke čtení [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Vrací:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Vrací správce motivu. Pouze ke čtní [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Vrací:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Vrací styl textu poznámek. Pouze ke čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslicích vodítek pro hlavní snímek s poznámkami. Pouze ke čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Přidání nového vodorovného kreslicího vodítka pod střed snímku
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)