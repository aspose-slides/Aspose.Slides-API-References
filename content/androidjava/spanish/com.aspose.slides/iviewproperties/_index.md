---
title: IViewProperties
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Propiedades de vista a nivel de presentación.
type: docs
url: /es/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Propiedades de vista a nivel de presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLastView()](#getLastView--) | Especifica el modo de vista que se usó cuando el documento de presentación se guardó por última vez. |
| [setLastView(int value)](#setLastView-int-) | Especifica el modo de vista que se usó cuando el documento de presentación se guardó por última vez. |
| [getShowComments()](#getShowComments--) | Especifica si los comentarios de la diapositiva deben mostrarse. |
| [setShowComments(byte value)](#setShowComments-byte-) | Especifica si los comentarios de la diapositiva deben mostrarse. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Especifica las propiedades de vista comunes asociadas al modo de vista de diapositiva. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Especifica las propiedades de vista comunes asociadas al modo de vista de notas. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representa las propiedades de vista normal. |
| [getGridSpacing()](#getGridSpacing--) | Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Especifica el modo de vista que se usó cuando el documento de presentación se guardó por última vez. Lectura/escritura [ViewType](../../com.aspose.slides/viewtype).

**Devuelve:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Especifica el modo de vista que se usó cuando el documento de presentación se guardó por última vez. Lectura/escritura [ViewType](../../com.aspose.slides/viewtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Especifica si los comentarios de la diapositiva deben mostrarse. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Especifica si los comentarios de la diapositiva deben mostrarse. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Especifica las propiedades de vista comunes asociadas al modo de vista de diapositiva. Solo lectura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Devuelve:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Especifica las propiedades de vista comunes asociadas al modo de vista de notas. Solo lectura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Devuelve:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Representa las propiedades de vista normal. La vista normal consta de tres regiones de contenido: la propia diapositiva, una región de contenido lateral y una región de contenido inferior. Solo lectura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Devuelve:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
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
public abstract void setGridSpacing(float value)
```

Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Lectura/escritura float.

--------------------

> ```
> El siguiente fragmento de código muestra cómo cambiar el espaciado de la cuadrícula en una presentación de PowerPoint.
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