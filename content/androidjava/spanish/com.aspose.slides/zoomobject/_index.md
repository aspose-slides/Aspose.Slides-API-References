---
title: ZoomObject
second_title: Referencia de API Java para Aspose.Slides para Android
description: Representa un objeto Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/zoomobject/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Representa un objeto Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getImageType()](#getImageType--) | Obtiene o establece el tipo de imagen de un objeto zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtiene o establece el tipo de imagen de un objeto zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtiene o establece el comportamiento de navegación en la presentación. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtiene o establece el comportamiento de navegación en la presentación. |
| [getShowBackground()](#getShowBackground--) | Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. |
| [getZoomImage()](#getZoomImage--) | Obtiene o establece la imagen del objeto zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtiene o establece la imagen del objeto zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtiene o establece la duración de la transición entre Zoom y la diapositiva. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtiene o establece la duración de la transición entre Zoom y la diapositiva. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Obtiene o establece el tipo de imagen de un objeto zoom. Lectura/escritura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor predeterminado: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Especifica si el objeto Zoom está usando la vista preliminar de la diapositiva o una imagen de portada.

**Devuelve:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Obtiene o establece el tipo de imagen de un objeto zoom. Lectura/escritura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor predeterminado: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Especifica si el objeto Zoom está usando la vista preliminar de la diapositiva o una imagen de portada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Obtiene o establece el comportamiento de navegación en la presentación. Lectura/escritura boolean. Valor predeterminado: false

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor verdadero de la propiedad especifica el comportamiento de navegación de regreso al elemento principal en la presentación.

**Devuelve:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Obtiene o establece el comportamiento de navegación en la presentación. Lectura/escritura boolean. Valor predeterminado: false

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor verdadero de la propiedad especifica el comportamiento de navegación de regreso al elemento principal en la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Lectura/escritura boolean. Valor predeterminado: true

--------------------

> ```
> el ejemplo muestra la eliminación del fondo de una imagen de un objeto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Lectura/escritura boolean. Valor predeterminado: true

--------------------

> ```
> el ejemplo muestra la eliminación del fondo de una imagen de un objeto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Obtiene o establece la imagen del objeto zoom. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> el ejemplo demuestra cómo cambiar una imagen de un objeto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Obtiene o establece la imagen del objeto zoom. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> el ejemplo demuestra cómo cambiar una imagen de un objeto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Obtiene o establece la duración de la transición entre Zoom y la diapositiva. Lectura/escritura float. Valor predeterminado: 1.0f

--------------------

> ```
> el ejemplo muestra cómo cambiar la duración de la transición entre Zoom y la diapositiva:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Si no se especifica (TransitionDur = 0), se usará la transición de la diapositiva de destino y los tiempos asociados a esa transición.

**Devuelve:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Obtiene o establece la duración de la transición entre Zoom y la diapositiva. Lectura/escritura float. Valor predeterminado: 1.0f

--------------------

> ```
> el ejemplo muestra cómo cambiar la duración de la transición entre Zoom y la diapositiva:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Si no se especifica (TransitionDur = 0), se usará la transición de la diapositiva de destino y los tiempos asociados a esa transición.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |