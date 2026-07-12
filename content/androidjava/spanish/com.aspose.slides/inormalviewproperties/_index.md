---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /es/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Representa las propiedades de la vista normal. La vista normal consta de tres regiones de contenido: la diapositiva en sí, una región de contenido lateral y una región de contenido inferior.

## Métodos

| Método | Descripción |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Especifica si la aplicación debe mostrar íconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Especifica si la aplicación debe mostrar íconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. |
| [getVerticalBarState()](#getVerticalBarState--) | Especifica el estado en el que se debe mostrar la barra del divisor vertical. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Especifica el estado en el que se debe mostrar la barra del divisor vertical. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Especifica el estado en el que se debe mostrar la barra del divisor horizontal. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Especifica el estado en el que se debe mostrar la barra del divisor horizontal. |
| [getPreferSingleView()](#getPreferSingleView--) | Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. |
| [getRestoredLeft()](#getRestoredLeft--) | Este elemento especifica el dimensionamiento de la región de contenido lateral de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). |
| [getRestoredTop()](#getRestoredTop--) | Este elemento especifica el dimensionamiento de la región superior de la diapositiva de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Especifica si la aplicación debe mostrar íconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. Lectura/escritura booleano.

**Devuelve:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Especifica si la aplicación debe mostrar íconos al visualizar contenido de esquema en cualquiera de las regiones de contenido del modo de vista normal. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. Lectura/escritura booleano.

**Devuelve:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Especifica si el divisor vertical debe ajustarse a un estado minimizado cuando la región lateral es lo suficientemente pequeña. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Especifica el estado en el que se debe mostrar la barra del divisor vertical. Una barra del divisor vertical separa la diapositiva de la región de contenido lateral.

**Devuelve:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Especifica el estado en el que se debe mostrar la barra del divisor vertical. Una barra del divisor vertical separa la diapositiva de la región de contenido lateral.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Especifica el estado en el que se debe mostrar la barra del divisor horizontal. Una barra del divisor horizontal separa la diapositiva de la región de contenido situada debajo de la diapositiva.

**Devuelve:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Especifica el estado en el que se debe mostrar la barra del divisor horizontal. Una barra del divisor horizontal separa la diapositiva de la región de contenido situada debajo de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. Si está habilitado, la aplicación puede elegir mostrar una de las regiones de contenido en toda la ventana. Lectura/escritura booleano.

**Devuelve:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Especifica si el usuario prefiere ver una región de contenido único a pantalla completa en lugar de la vista normal estándar con tres regiones de contenido. Si está habilitado, la aplicación puede elegir mostrar una de las regiones de contenido en toda la ventana. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Este elemento especifica el dimensionamiento de la región de contenido lateral de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo lectura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Devuelve:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Este elemento especifica el dimensionamiento de la región superior de la diapositiva de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizado ni maximizado). Solo lectura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Devuelve:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)