---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /nl/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Stelt een manager voor die u in staat stelt placeholders toe te voegen aan de layoutdia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst in een verticale richting. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud vast te houden. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud in een verticale richting vast te houden. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een afbeelding vast te houden. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Chart vast te houden. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Table vast te houden. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een SmartArt-diagram vast te houden. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Media-object vast te houden. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutdia om een online afbeelding vast te houden. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om inhoud vast te houden, zoals een afbeelding, tabel, media of tekst in een verticale richting.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud vast te houden.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om tekstinhoud in een verticale richting vast te houden.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een afbeelding vast te houden.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Chart vast te houden.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Table vast te houden.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe je de Table placeholder-vorm aan de layout-dia kunt toevoegen.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een SmartArt-diagram vast te houden.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe je de SmartArt placeholder-vorm aan de layout-dia kunt toevoegen.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een Media-object vast te houden.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Voegt een nieuw placeholder-vorm toe aan de layoutdia om een online afbeelding vast te houden.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Online Image placeholder.