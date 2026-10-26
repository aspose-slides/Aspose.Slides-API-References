---
title: MasterNotesSlide
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia do Java API
description: Reprezentuje slajd nadrzędny notatek.
type: docs
url: /pl/com.aspose.slides/masternotesslide/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Reprezentuje slajd nadrzędny notatek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu notatek nadrzędnych. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera motywu. |
| [getNotesStyle()](#getNotesStyle--) | Zwraca styl tekstu notatek. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu notatek nadrzędnych. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach. Dla samego slajdu nadrzędnego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach. Dla samego slajdu nadrzędnego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter slajdu notatek nadrzędnych. Tylko do odczytu [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Zwraca:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Zwraca menedżera motywu. Tylko do odczytu [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Zwraca:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


Zwraca styl tekstu notatek. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Zwraca kolekcję przewodników rysowania dla slajdu notatek nadrzędnych. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Dodawanie nowej poziomej linii rysunkowej pod środkiem slajdu
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)