---
title: MasterNotesSlide
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje główny slajd notatek.
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

Reprezentuje główny slajd notatek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na master-slajdzie mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na master-slajdzie mają być wyświetlane na slajdach, czy nie. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżer HeaderFooter master-slajdu notatek. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżer motywu. |
| [getNotesStyle()](#getNotesStyle--) | Zwraca styl tekstu notatek. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla master-slajdu notatek. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Określa, czy kształty na master-slajdzie mają być wyświetlane na slajdach, czy nie. Dla samego master-slajdu ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Określa, czy kształty na master-slajdzie mają być wyświetlane na slajdach, czy nie. Dla samego master-slajdu ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżer HeaderFooter master-slajdu notatek. Tylko do odczytu [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Zwraca:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Zwraca menedżer motywu. Tylko do odczytu [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

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

Zwraca kolekcję przewodników rysowania dla master-slajdu notatek. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Dodawanie nowej poziomej linii prowadzącej poniżej środka slajdu
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)