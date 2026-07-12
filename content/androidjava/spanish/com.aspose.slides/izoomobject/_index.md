---
title: IZoomObject
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un objeto Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/izoomobject/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Representa un objeto Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getImageType()](#getImageType--) | Obtiene o establece el tipo de imagen de un objeto Zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtiene o establece el tipo de imagen de un objeto Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. |
| [getShowBackground()](#getShowBackground--) | Obtiene o establece el valor que indica si el Zoom utilizará el fondo de la diapositiva de destino. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtiene o establece el valor que indica si el Zoom utilizará el fondo de la diapositiva de destino. |
| [getZoomImage()](#getZoomImage--) | Obtiene o establece la imagen para el objeto Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtiene o establece la imagen para el objeto Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtiene o establece la duración de la transición entre Zoom y diapositiva. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtiene o establece la duración de la transición entre Zoom y diapositiva. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Obtiene o establece el tipo de imagen de un objeto Zoom. Lectura/escritura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor predeterminado: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Especifica si el objeto Zoom está utilizando la vista previa de la diapositiva o una imagen de portada.

**Devuelve:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Obtiene o establece el tipo de imagen de un objeto Zoom. Lectura/escritura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor predeterminado: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Especifica si el objeto Zoom está utilizando la vista previa de la diapositiva o una imagen de portada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Lectura/escritura boolean. Valor predeterminado: false

--------------------

> ```
> Example:
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

El valor verdadero de la propiedad indica el comportamiento de navegación de retorno al elemento principal en la presentación de diapositivas.

**Devuelve:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Lectura/escritura boolean. Valor predeterminado: false

--------------------

> ```
> Example:
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

El valor verdadero de la propiedad indica el comportamiento de navegación de retorno al elemento principal en la presentación de diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Obtiene o establece el valor que indica si el Zoom utilizará el fondo de la diapositiva de destino. Lectura/escritura boolean. Valor predeterminado: true

--------------------

> ```
> El ejemplo muestra cómo eliminar el fondo de una imagen de un objeto Zoom:
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
public abstract void setShowBackground(boolean value)
```


Obtiene o establece el valor que indica si el Zoom utilizará el fondo de la diapositiva de destino. Lectura/escritura boolean. Valor predeterminado: true

--------------------

> ```
> El ejemplo muestra cómo eliminar el fondo de una imagen de un objeto Zoom:
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
public abstract IPPImage getZoomImage()
```


Obtiene o establece la imagen para el objeto Zoom. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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
public abstract void setZoomImage(IPPImage value)
```


Obtiene o establece la imagen para el objeto Zoom. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> El ejemplo muestra cómo cambiar una imagen de un objeto Zoom:
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
public abstract float getTransitionDuration()
```


Obtiene o establece la duración de la transición entre Zoom y diapositiva. Lectura/escritura float. Valor predeterminado: 1.0f

--------------------

> ```
> el ejemplo muestra cómo cambiar la duración de la transición entre Zoom y diapositiva:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Si no se especifica (TransitionDur = 0), se utilizará la transición de la diapositiva de destino y los tiempos asociados a esa transición.

**Devuelve:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Obtiene o establece la duración de la transición entre Zoom y diapositiva. Lectura/escritura float. Valor predeterminado: 1.0f

--------------------

> ```
> el ejemplo muestra cómo cambiar la duración de la transición entre Zoom y diapositiva:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Si no se especifica (TransitionDur = 0), se utilizará la transición de la diapositiva de destino y los tiempos asociados a esa transición.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |