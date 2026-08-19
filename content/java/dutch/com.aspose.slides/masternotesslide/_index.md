---
title: MasterNotesSlide
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt masterdia voor notities.
type: docs
url: /nl/com.aspose.slides/masternotesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Vertegenwoordigt masterdia voor notities.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterdia wel of niet moeten worden getoond op dia's. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterdia wel of niet moeten worden getoond op dia's. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter-beheerder van de masternotitiedia. |
| [getThemeManager()](#getThemeManager--) | Retourneert de themabeheerder. |
| [getNotesStyle()](#getNotesStyle--) | Retourneert de stijl van een notitietekst. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een verzameling tekenrichtlijnen voor de masternotitiedia. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificeert of vormen op de masterdia wel of niet moeten worden getoond op dia's. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificeert of vormen op de masterdia wel of niet moeten worden getoond op dia's. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter-beheerder van de masternotitiedia. Alleen-lezen [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retourneert:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Retourneert de themabeheerder. Alleen-lezen [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourneert:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


Retourneert de stijl van een notitietekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een verzameling tekenrichtlijnen voor de masternotitiedia. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Voegt de nieuwe horizontale tekenrichtlijn toe onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)