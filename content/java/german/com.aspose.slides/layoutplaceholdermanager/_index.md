---
title: LayoutPlaceholderManager
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Manager dar, der es Ihnen ermöglicht, Platzhalter zur Layoutfolie hinzuzufügen.
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

Stellt einen Manager dar, der es Ihnen ermöglicht, Platzhalter zur Layoutfolie hinzuzufügen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text hält. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung hält. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Textinhalt hält. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Textinhalt in vertikaler Richtung hält. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Bild hält. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Diagramm hält. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das eine Tabelle hält. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein SmartArt-Diagramm hält. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Medienobjekt hält. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Online-Bild hält. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhaltsplatzhalter.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Inhaltsplatzhalter (vertikal).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Textinhalt hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Textplatzhalter.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das Textinhalt in vertikaler Richtung hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Textplatzhalter (vertikal).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Bild hält.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Bildplatzhalter.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Diagramm hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Diagrammplatzhalter.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das eine Tabelle hält.

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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Tabellenplatzhalter.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein SmartArt-Diagramm hält.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem SmartArt-Platzhalter.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Medienobjekt hält.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Medienplatzhalter.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, das ein Online-Bild hält.

--------------------

> ```
> Das folgende Beispiel zeigt, wie das Online-Bild-Platzhalter-Shape zur Layoutfolie hinzugefügt wird.
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

**Rückgabe:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Erstellt [IAutoShape](../../com.aspose.slides/iautoshape) mit einem Online-Bildplatzhalter.