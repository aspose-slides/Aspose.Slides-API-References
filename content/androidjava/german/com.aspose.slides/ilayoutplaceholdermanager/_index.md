---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt einen Manager dar, der das Hinzufügen von Platzhaltern zur Layout-Folie ermöglicht.
type: docs
url: /de/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Stellt einen Manager dar, der das Hinzufügen von Platzhaltern zur Layout-Folie ermöglicht.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Inhalt zu halten, z. B. ein Bild, eine Tabelle, Medien oder Text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Inhalt zu halten, z. B. ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Textinhalt zu halten. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Textinhalt in vertikaler Richtung zu halten. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Bild zu halten. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Diagramm zu halten. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um eine Tabelle zu halten. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein SmartArt-Diagramm zu halten. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Medienobjekt zu halten. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Online-Bild zu halten. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Inhalt zu halten, z. B. ein Bild, eine Tabelle, Medien oder Text.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Content placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhalts-Platzhalter.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Inhalt zu halten, z. B. ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Content (Vertical) placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhalts (Vertikal) Platzhalter.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Textinhalt zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Text placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text-Platzhalter.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Textinhalt in vertikaler Richtung zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Text (Vertical) placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Text (Vertikal) Platzhalter.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Bild zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Picture placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Bild-Platzhalter.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Diagramm zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Chart placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Diagramm-Platzhalter.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um eine Tabelle zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Table placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Tabellen-Platzhalter.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein SmartArt-Diagramm zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die SmartArt placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem SmartArt-Platzhalter.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Medienobjekt zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Media placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Medien-Platzhalter.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um ein Online-Bild zu halten.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man die Online Image placeholder shape zur Layout-Folie hinzufügt.
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
| x | float | Die X-Koordinate der neuen Platzhalter-Form. |
| y | float | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | float | Die Breite der neuen Platzhalter-Form. |
| height | float | Die Höhe der neuen Platzhalter-Form. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Online-Bild-Platzhalter.