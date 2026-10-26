---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /es/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Representa un nodo de un diagrama SmartArt.

## Métodos

| Método | Descripción |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Devuelve colecciones de todos los nodos hijos del nodo actual. |
| [getShapes()](#getShapes--) | Devuelve colecciones de todas las formas asociadas al nodo. |
| [getTextFrame()](#getTextFrame--) | Devuelve o establece el texto del nodo. |
| [isAssistant()](#isAssistant--) | Devuelve o establece el nodo como asistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Devuelve o establece el nodo como asistente. |
| [getLevel()](#getLevel--) | Devuelve el nivel de anidamiento del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para la viñeta de un nodo. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [setPosition(int value)](#setPosition-int-) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [isHidden()](#isHidden--) | Devuelve true si este nodo es un nodo oculto en el modelo de datos. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Devuelve o establece el tipo de diseño de organigrama asociado al nodo actual. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Devuelve o establece el tipo de diseño de organigrama asociado al nodo actual. |
| [remove()](#remove--) | Elimina el nodo actual. |

### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Devuelve colecciones de todos los nodos hijos del nodo actual. Sólo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Devuelve:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Devuelve colecciones de todas las formas asociadas al nodo. Sólo lectura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Devuelve:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Devuelve o establece el texto del nodo. Sólo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Devuelve el nivel de anidamiento del nodo. Sólo lectura int.

**Devuelve:**
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para la viñeta de un nodo. Nota: puede devolver null para ciertos tipos de diseño de SmartArt que no proporcionan viñetas para los nodos. Sólo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Devuelve:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Devuelve true si este nodo es un nodo oculto en el modelo de datos. Sólo lectura boolean.

**Devuelve:**
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Devuelve o establece el tipo de diseño de organigrama asociado al nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Devuelve:**
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Devuelve o establece el tipo de diseño de organigrama asociado al nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```

Elimina el nodo actual.

**Devuelve:**
boolean - true si se eliminó correctamente, de lo contrario false.