---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een manager voor die het mogelijk maakt placeholders aan de layoutdia toe te voegen.
type: docs
url: /nl/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Stelt een manager voor die het mogelijk maakt placeholders aan de layoutdia toe te voegen.
## Methoden

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst in een verticale richting. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud te bevatten. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud in een verticale richting te bevatten. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een afbeelding te bevatten. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een diagram te bevatten. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een tabel te bevatten. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een SmartArt-diagram te bevatten. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een media-object te bevatten. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een online afbeelding te bevatten. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst in een verticale richting.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud te bevatten.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud in een verticale richting te bevatten.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een afbeelding te bevatten.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een diagram te bevatten.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een tabel te bevatten.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een SmartArt-diagram te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe u de SmartArt placeholder-vorm aan de layoutdia kunt toevoegen.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een media-object te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe u de Media placeholder-vorm aan de layoutdia kunt toevoegen.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een online afbeelding te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe u de Online Image placeholder-vorm aan de layoutdia kunt toevoegen.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Online Image placeholder.