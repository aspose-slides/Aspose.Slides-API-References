---
title: LayoutPlaceholderManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un manager che consente di aggiungere segnaposti alla diapositiva di layout.
type: docs
url: /it/com.aspose.slides/layoutplaceholdermanager/
---
**Ereditarietà:**  
java.lang.Object

**Tutte le interfacce implementate:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Rappresenta un manager che consente di aggiungere segnaposti alla diapositiva di layout.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo in una direzione verticale. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti testuali. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti testuali in una direzione verticale. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere una tabella. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un diagramma SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine online. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo.

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
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo in una direzione verticale.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Content (Vertical) alla diapositiva di layout.
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
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti testuali.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Text alla diapositiva di layout.
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
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti testuali in una direzione verticale.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Text (Vertical) alla diapositiva di layout.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto Text (Vertical).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Picture alla diapositiva di layout.
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
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Chart alla diapositiva di layout.
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
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere una tabella.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Table alla diapositiva di layout.
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
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
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

**Restituisce:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Creato [IAutoShape](../../com.aspose.slides/iautoshape) con un segnaposto SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Media alla diapositiva di layout.
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
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un'immagine online.

--------------------

> ```
> Il seguente esempio mostra come aggiungere la forma segnaposto Online Image alla diapositiva di layout.
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