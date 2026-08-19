---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Rappresenta il gestore che consente di aggiungere segnaposto alla diapositiva di layout.
type: docs
url: /it/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Rappresenta il gestore che consente di aggiungere segnaposto alla diapositiva di layout.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo in direzione verticale. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti di testo. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti di testo in direzione verticale. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere una tabella. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un diagramma SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine online. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo in direzione verticale.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti di testo.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti di testo in direzione verticale.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere una tabella.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un diagramma SmartArt.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto SmartArt alla diapositiva di layout.
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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine online.

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

**Valore restituito:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un Online Image placeholder.