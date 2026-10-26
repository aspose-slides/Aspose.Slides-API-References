---
title: LayoutPlaceholderManager
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un administrador que le permite agregar marcadores de posición a la diapositiva de diseño.
type: docs
url: /es/com.aspose.slides/layoutplaceholdermanager/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Representa un administrador que le permite agregar marcadores de posición a la diapositiva de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, medio o texto. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, medio o texto en dirección vertical. |
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
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, medio o texto.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de contenido.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, medio o texto en dirección vertical.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de contenido (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de texto.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto en dirección vertical.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada X de la nueva forma de marcador de posición. |
| y | float | La coordenada Y de la nueva forma de marcador de posición. |
| width | float | El ancho de la nueva forma de marcador de posición. |
| height | float | La altura de la nueva forma de marcador de posición. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de texto (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de imagen.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de gráfico.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de tabla.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
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
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un objeto multimedia.

--------------------

> ```
> El siguiente ejemplo muestra cómo agregar la forma de marcador de posición Media a la diapositiva de diseño.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición multimedia.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen en línea.

--------------------

> ```
> El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Imagen en línea a la diapositiva de diseño.
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
[IAutoShape](../../com.aspose.slides/iautoshape) - Creado [IAutoShape](../../com.aspose.slides/iautoshape) con un marcador de posición de imagen en línea.