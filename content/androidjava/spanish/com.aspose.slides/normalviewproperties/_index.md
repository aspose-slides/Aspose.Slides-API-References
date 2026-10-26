---
title: NormalViewProperties
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa las propiedades de la vista normal.
type: docs
url: /es/com.aspose.slides/normalviewproperties/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Representa las propiedades de la vista normal. La vista normal consta de tres regiones de contenido: la diapositiva misma, una región de contenido lateral y una región de contenido inferior.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instanciar un objeto de presentación que representa un archivo de presentación
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Especifica si la aplicación debe mostrar iconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Especifica si la aplicación debe mostrar iconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. |
| [getVerticalBarState()](#getVerticalBarState--) | Especifica el estado en el que se debe mostrar la barra del divisor vertical. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Especifica el estado en el que se debe mostrar la barra del divisor vertical. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Especifica el estado en el que se debe mostrar la barra del divisor horizontal. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Especifica el estado en el que se debe mostrar la barra del divisor horizontal. |
| [getPreferSingleView()](#getPreferSingleView--) | Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. |
| [getRestoredLeft()](#getRestoredLeft--) | Este elemento especifica el tamaño de la región de contenido lateral de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). |
| [getRestoredTop()](#getRestoredTop--) | Este elemento especifica el tamaño de la región superior de la diapositiva de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Especifica si la aplicación debe mostrar iconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. Lectura/escritura booleano.

**Devuelve:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Especifica si la aplicación debe mostrar iconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. Lectura/escritura booleano.

**Devuelve:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Especifica el estado en el que se debe mostrar la barra del divisor vertical. Una barra del divisor vertical separa la diapositiva de la región de contenido lateral.

**Devuelve:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Especifica el estado en el que se debe mostrar la barra del divisor vertical. Una barra del divisor vertical separa la diapositiva de la región de contenido lateral.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Especifica el estado en el que se debe mostrar la barra del divisor horizontal. Una barra del divisor horizontal separa la diapositiva de la región de contenido situada bajo la diapositiva.

**Devuelve:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Especifica el estado en el que se debe mostrar la barra del divisor horizontal. Una barra del divisor horizontal separa la diapositiva de la región de contenido situada bajo la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. Si está habilitado, la aplicación puede elegir mostrar una de las regiones de contenido en toda la ventana. Lectura/escritura booleano.

**Devuelve:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. Si está habilitado, la aplicación puede elegir mostrar una de las regiones de contenido en toda la ventana. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Este elemento especifica el tamaño de la región de contenido lateral de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo lectura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Devuelve:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Este elemento especifica el tamaño de la región superior de la diapositiva de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo lectura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Devuelve:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)