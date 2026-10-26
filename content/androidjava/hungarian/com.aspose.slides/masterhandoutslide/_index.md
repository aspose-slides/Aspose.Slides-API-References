---
title: MasterHandoutSlide
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: A kézhezadások mesterdiapozitívját képviseli.
type: docs
url: /hu/com.aspose.slides/masterhandoutslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

A kézhezadások mesterdiapozitívját képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdiapozitív alakzatai megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdiapozitív alakzatai megjelenjenek-e a diákon vagy sem. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mester kézhezadási diára a HeaderFooter kezelőt. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a témakezelőt. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a mester kézhezadási diára vonatkozó rajzsegélyekből. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a mesterdiapozitív alakzatai megjelenjenek-e a diákon vagy sem. A mesterdiapozitív esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Visszaad:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdiapozitív alakzatai megjelenjenek-e a diákon vagy sem. A mesterdiapozitív esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mester kézhezadási dián a HeaderFooter kezelőt. Csak olvasható [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Visszaad:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a témakezelőt. Csak olvasható [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszaad:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a mester kézhezadási diára vonatkozó rajzsegélyekből. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Új vízszintes rajzsegély hozzáadása a dia középpontja felett
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszaad:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)