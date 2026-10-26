---
title: MasterHandoutSlide
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje slajd główny dla notatek.
type: docs
url: /pl/com.aspose.slides/masterhandoutslide/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Reprezentuje slajd główny dla notatek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu głównego notatek. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera motywu. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu głównego notatek. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Dla samego slajdu głównego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Dla samego slajdu głównego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter slajdu głównego notatek. Tylko do odczytu [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Zwraca:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Zwraca menedżera motywu. Tylko do odczytu [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Zwraca:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Zwraca kolekcję przewodników rysowania dla slajdu głównego notatek. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Dodawanie nowej poziomej linii prowadzącej powyżej środka slajdu
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)