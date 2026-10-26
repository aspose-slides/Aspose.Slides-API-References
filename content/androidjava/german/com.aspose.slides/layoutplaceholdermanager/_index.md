---
title: LayoutPlaceholderManager
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt einen Manager dar, der es ermöglicht, Platzhalter zur Layout-Folie hinzuzufügen.
type: docs
url: /de/com.aspose.slides/layoutplaceholdermanager/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Stellt einen Manager dar, der es ermöglicht, Platzhalter zur Layout-Folie hinzuzufügen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text zu halten. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Textinhalt zu halten. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Textinhalt in vertikaler Richtung zu halten. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Bild zu halten. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Diagramm zu halten. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um eine Tabelle zu halten. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein SmartArt-Diagramm zu halten. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Medienobjekt zu halten. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Online-Bild zu halten. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text zu halten.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhalts-Platzhalter.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhalts-Platzhalter (Vertikal).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Textinhalt zu halten.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text-Platzhalter.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Textinhalt in vertikaler Richtung zu halten.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text-Platzhalter (Vertikal).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Bild zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Picture-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Bild-Platzhalter.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Diagramm zu halten.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Diagramm-Platzhalter.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um eine Tabelle zu halten.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Tabellen-Platzhalter.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein SmartArt-Diagramm zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das SmartArt-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem SmartArt-Platzhalter.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Medienobjekt zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Media-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Medien-Platzhalter.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Online-Bild zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Online Image-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | float | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | float | Die Breite des neuen Platzhalter-Shapes. |
| height | float | Die Höhe des neuen Platzhalter-Shapes. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Online-Bild-Platzhalter.