---
title: LayoutPlaceholderManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een manager voor die het mogelijk maakt placeholders toe te voegen aan de layout-slide.
type: docs
url: /nl/com.aspose.slides/layoutplaceholdermanager/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Stelt een manager voor die het mogelijk maakt placeholders toe te voegen aan de layout-slide.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst in verticale richting. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om tekstinhoud te bevatten. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om tekstinhoud in verticale richting te bevatten. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een afbeelding te bevatten. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een grafiek te bevatten. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een tabel te bevatten. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een SmartArt-diagram te bevatten. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een media-object te bevatten. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een online afbeelding te bevatten. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content-placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst in verticale richting.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Content (Vertical) placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Content (Vertical)-placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om tekstinhoud te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Text placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text-placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om tekstinhoud in verticale richting te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Text (Vertical) placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Text (Vertical)-placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een afbeelding te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Picture placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Picture-placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een grafiek te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Chart placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Chart-placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een tabel te bevatten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De X-coördinaat van de nieuwe placeholder-vorm. |
| y | float | De Y-coördinaat van de nieuwe placeholder-vorm. |
| width | float | De breedte van de nieuwe placeholder-vorm. |
| height | float | De hoogte van de nieuwe placeholder-vorm. |

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Table-placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een SmartArt-diagram te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de SmartArt placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een SmartArt-placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een media-object te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Media placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Media-placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Voegt een nieuw placeholder-vorm toe aan de layoutsslide om een online afbeelding te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe je de Online Image placeholder vorm aan de layout slide kunt toevoegen.
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

**Retour:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Aangemaakt [IAutoShape](../../com.aspose.slides/iautoshape) met een Online Image-placeholder.