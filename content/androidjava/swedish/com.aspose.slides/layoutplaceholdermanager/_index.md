---
title: LayoutPlaceholderManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som tillåter dig att lägga till platshållare på layoutbilden.
type: docs
url: /sv/com.aspose.slides/layoutplaceholdermanager/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Representerar en hanterare som låter dig lägga till platshållare i layoutbilden.
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
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Lägger till en ny platshållarform på layoutbilden för att hålla en onlinebild. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text.

--------------------

> ```
> Följande exempel visar hur du lägger till Content placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en innehållsplatshållare.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text i vertikal riktning.

--------------------

> ```
> Följande exempel visar hur du lägger till Content (Vertical) placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en innehåll (vertikal) platshållare.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll.

--------------------

> ```
> Följande exempel visar hur du lägger till Text placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en textplatshållare.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla textinnehåll i vertikal riktning.

--------------------

> ```
> Följande exempel visar hur du lägger till Text (Vertical) placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en text (vertikal) platshållare.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en bild.

--------------------

> ```
> Följande exempel visar hur du lägger till Picture placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en bildplatshållare.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett diagram.

--------------------

> ```
> Följande exempel visar hur du lägger till Chart placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en diagramplatshållare.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en tabell.

--------------------

> ```
> Följande exempel visar hur du lägger till Table placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en tabellplatshållare.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett SmartArt-diagram.

--------------------

> ```
> Följande exempel visar hur du lägger till SmartArt placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en SmartArt-platshållare.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla ett mediaobjekt.

--------------------

> ```
> Följande exempel visar hur du lägger till Media placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en media-platshållare.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Lägger till en ny platshållarform på layoutbilden för att hålla en onlinebild.

--------------------

> ```
> Följande exempel visar hur du lägger till Online Image placeholder shape på layoutbilden.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Skapade [IAutoShape](../../com.aspose.slides/iautoshape) med en onlinebild-platshållare.