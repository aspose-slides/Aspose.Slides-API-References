---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /de/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Stellt einen Manager dar, der das Hinzufügen von Platzhaltern zur Layout-Folien ermöglicht.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text enthält. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung enthält. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Textinhalt enthält. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Textinhalt in vertikaler Richtung enthält. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Bild enthält. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Diagramm enthält. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das eine Tabelle enthält. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein SmartArt-Diagramm enthält. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Medienobjekt enthält. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Online-Bild enthält. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text enthält.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Content-Platzhalter.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung enthält.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Content (Vertical)-Platzhalter.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Textinhalt enthält.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Text-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text-Platzhalter.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das Textinhalt in vertikaler Richtung enthält.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Text (Vertikal) Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text (Vertical)-Platzhalter.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Bild enthält.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Picture-Platzhalter.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Diagramm enthält.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Chart-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Chart-Platzhalter.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das eine Tabelle enthält.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Table-Platzhalter-Shape zur Layout-Folie hinzugefügt wird.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Table-Platzhalter.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein SmartArt-Diagramm enthält.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem SmartArt-Platzhalter.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Medienobjekt enthält.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Media-Platzhalter.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, das ein Online-Bild enthält.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Online Image-Platzhalter.