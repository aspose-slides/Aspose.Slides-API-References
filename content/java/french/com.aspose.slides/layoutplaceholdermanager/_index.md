---
title: LayoutPlaceholderManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le gestionnaire qui vous permet d’ajouter des espaces réservés à la diapositive de mise en page.
type: docs
url: /fr/com.aspose.slides/layoutplaceholdermanager/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Représente le gestionnaire qui vous permet d’ajouter des espaces réservés à la diapositive de mise en page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du contenu, tel qu’une image, un tableau, un média ou du texte. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du contenu, tel qu’une image, un tableau, un média ou du texte dans une direction verticale. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du texte. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du texte dans une direction verticale. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir une image. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un diagramme. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un tableau. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un diagramme SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un objet multimédia. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir une image en ligne. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du contenu, tel qu’une image, un tableau, un média ou du texte.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Content.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du contenu, tel qu’une image, un tableau, un média ou du texte dans une direction verticale.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Content (Vertical).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du texte.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Text.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir du texte dans une direction verticale.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Text (Vertical).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir une image.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Picture.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un diagramme.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Chart.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un tableau.

--------------------

> ```
> L'exemple suivant montre comment ajouter la forme d'espace réservé Table à la diapositive de mise en page.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Table.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un diagramme SmartArt.

--------------------

> ```
> L'exemple suivant montre comment ajouter la forme d'espace réservé SmartArt à la diapositive de mise en page.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir un objet multimédia.

--------------------

> ```
> L'exemple suivant montre comment ajouter la forme d'espace réservé Media à la diapositive de mise en page.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Media.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Ajoute une nouvelle forme de substitut à la diapositive de mise en page pour contenir une image en ligne.

--------------------

> ```
> L'exemple suivant montre comment ajouter la forme d'espace réservé Online Image à la diapositive de mise en page.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée X de la nouvelle forme de substitut. |
| y | float | La coordonnée Y de la nouvelle forme de substitut. |
| width | float | La largeur de la nouvelle forme de substitut. |
| height | float | La hauteur de la nouvelle forme de substitut. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Créé [IAutoShape](../../com.aspose.slides/iautoshape) avec un espace réservé de type Online Image.