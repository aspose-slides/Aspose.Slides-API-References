---
title: MasterNotesSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de masterdia voor notities.
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

Stelt de masterdia voor notities voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterdia moeten worden weergegeven op dia&#x27;s of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterdia moeten worden weergegeven op dia&#x27;s of niet. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter-beheerder van de master notitieslide. |
| [getThemeManager()](#getThemeManager--) | Retourneert de themabeheerder. |
| [getNotesStyle()](#getNotesStyle--) | Retourneert de stijl van een notitietekst. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een verzameling van tekeningsgidsen voor de master notitieslide. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificeert of vormen op de masterdia moeten worden weergegeven op dia&#x27;s of niet. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificeert of vormen op de masterdia moeten worden weergegeven op dia&#x27;s of niet. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter-beheerder van de master notitieslide. Alleen-lezen [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

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


Retourneert een verzameling van tekeningsgidsen voor de master notitieslide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Voeg de nieuwe horizontale tekenlijn toe onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)