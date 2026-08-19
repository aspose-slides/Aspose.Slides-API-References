---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Representerar en manager som låter dig lägga till platshållare på layoutbilden.
type: docs
url: /sv/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Representerar en manager som låter dig lägga till platshållare på layoutbilden.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text i vertikal riktning. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll i vertikal riktning. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla en bild. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla ett diagram. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla en tabell. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla ett SmartArt-diagram. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla ett mediaobjekt. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla en online-bild. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Content-platshållare.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text i vertikal riktning.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Content (Vertical) platshållare.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Text-platshållare.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll i vertikal riktning.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Text (Vertical) platshållare.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en bild.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Picture-platshållare.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett diagram.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Chart-platshållare.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en tabell.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Table-platshållare.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett SmartArt-diagram.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en SmartArt-platshållare.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett mediaobjekt.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Media-platshållare.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en online-bild.

--------------------

> ```
> Följande exempel visar hur man lägger till Online Image placeholder shape till layoutbilden.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya platshållarformen. |
| y | float | Y-koordinaten för den nya platshållarformen. |
| width | float | Bredden på den nya platshållarformen. |
| height | float | Höjden på den nya platshållarformen. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapad [IAutoShape](../../com.aspose.slides/iautoshape) med en Online Image-platshållare.