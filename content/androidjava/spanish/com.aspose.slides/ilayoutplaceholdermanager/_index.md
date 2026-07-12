---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /es/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Representa un administrador que permite agregar marcadores de posición a la diapositiva de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, multimedia o texto. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, multimedia o texto en dirección vertical. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto en dirección vertical. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un gráfico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una tabla. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un objeto multimedia. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen en línea. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, multimedia o texto.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, multimedia o texto en dirección vertical.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto en dirección vertical.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un gráfico.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una tabla.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama SmartArt.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un objeto multimedia.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen en línea.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición Online Image.