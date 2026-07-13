---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un manager che consente di aggiungere segnaposti alla diapositiva layout.
type: docs
url: /it/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Rappresenta un manager che consente di aggiungere segnaposti alla diapositiva layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti, come un'immagine, una tabella, un supporto multimediale o testo. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti, come un'immagine, una tabella, un supporto multimediale o testo in direzione verticale. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti testuali. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti testuali in direzione verticale. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un'immagine. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un grafico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere una tabella. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un diagramma SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un oggetto multimediale. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un'immagine online. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti, come un'immagine, una tabella, un supporto multimediale o testo.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti, come un'immagine, una tabella, un supporto multimediale o testo in direzione verticale.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti testuali.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuti testuali in direzione verticale.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un'immagine.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un grafico.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere una tabella.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un diagramma SmartArt.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un oggetto multimediale.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere un'immagine online.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata X della nuova forma segnaposto. |
| y | float | La coordinata Y della nuova forma segnaposto. |
| width | float | La larghezza della nuova forma segnaposto. |
| height | float | L'altezza della nuova forma segnaposto. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Online Image.