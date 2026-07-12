---
title: ViewProperties
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Propiedades de vista a nivel de presentación.
type: docs
url: /es/com.aspose.slides/viewproperties/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Propiedades de vista a nivel de presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLastView()](#getLastView--) | Especifica el modo de vista que se utilizó cuando se guardó por última vez el documento de presentación. |
| [setLastView(int value)](#setLastView-int-) | Especifica el modo de vista que se utilizó cuando se guardó por última vez el documento de presentación. |
| [getShowComments()](#getShowComments--) | Especifica si los comentarios de la diapositiva deben mostrarse. |
| [setShowComments(byte value)](#setShowComments-byte-) | Especifica si los comentarios de la diapositiva deben mostrarse. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representa las propiedades de vista normal. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Especifica las propiedades de vista comunes asociadas al modo de vista de diapositiva. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Especifica las propiedades de vista comunes asociadas al modo de vista de notas. |
| [getGridSpacing()](#getGridSpacing--) | Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Especifica el modo de vista que se utilizó cuando se guardó por última vez el documento de presentación. Lectura/escritura [ViewType](../../com.aspose.slides/viewtype).

**Devuelve:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Especifica el modo de vista que se utilizó cuando se guardó por última vez el documento de presentación. Lectura/escritura [ViewType](../../com.aspose.slides/viewtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Especifica si los comentarios de la diapositiva deben mostrarse. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Especifica si los comentarios de la diapositiva deben mostrarse. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Representa las propiedades de vista normal. La vista normal consta de tres regiones de contenido: la propia diapositiva, una región lateral de contenido y una región inferior de contenido. Solo lectura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Devuelve:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Especifica las propiedades de vista comunes asociadas al modo de vista de diapositiva. Solo lectura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Devuelve:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Especifica las propiedades de vista comunes asociadas al modo de vista de notas. Solo lectura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Devuelve:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Lectura/escritura float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor del espaciado de la cuadrícula debe ser un número positivo. El rango típico es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos).

**Devuelve:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Lectura/escritura float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor del espaciado de la cuadrícula debe ser un número positivo. El rango típico es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject