---
title: LayoutPlaceholderManager
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente le gestionnaire qui vous permet d'ajouter des espaces réservés à la diapositive maître.
type: docs
url: /fr/com.aspose.slides/layoutplaceholdermanager/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Représente le gestionnaire qui vous permet d'ajouter des espaces réservés à la diapositive maître.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte dans une direction verticale. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir du texte. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir du texte dans une direction verticale. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir une image. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir un graphique. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir un tableau. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir un diagramme SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir un objet média. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir une image en ligne. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text in a vertical direction.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold text content.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold text content in a vertical direction.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a picture.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a chart.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a table.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a SmartArt diagram.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Adds a new placeholder shape to the layout slide to hold a media object.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)


Ajoute une nouvelle forme d'espace réservé à la diapositive maître pour contenir une image en ligne.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme d'espace réservé. |
| y | float | La coordonnée Y de la nouvelle forme d'espace réservé. |
| width | float | La largeur de la nouvelle forme d'espace réservé. |
| height | float | La hauteur de la nouvelle forme d'espace réservé. |

**Valeur retournée :**
[IAutoShape](../../com.aspose.slides/iautoshape) - Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé d'image en ligne.