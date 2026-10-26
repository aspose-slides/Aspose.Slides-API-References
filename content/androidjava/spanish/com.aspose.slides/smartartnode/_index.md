---
title: SmartArtNode
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un nodo de un objeto SmartArt
type: docs
url: /es/com.aspose.slides/smartartnode/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Representa un nodo de un objeto SmartArt
## Métodos

| Método | Descripción |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Devuelve colecciones de todos los nodos hijos del nodo actual. |
| [getShapes()](#getShapes--) | Devuelve colecciones de todas las formas asociadas al nodo. |
| [getTextFrame()](#getTextFrame--) | Devuelve el marco de texto del nodo. |
| [isAssistant()](#isAssistant--) | Devuelve o establece el nodo como asistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Devuelve o establece el nodo como asistente. |
| [getLevel()](#getLevel--) | Devuelve el nivel de anidamiento del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para la viñeta de un nodo. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [setPosition(int value)](#setPosition-int-) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [isHidden()](#isHidden--) | Devuelve true si este nodo es un nodo oculto en el modelo de datos. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Devuelve o establece el tipo de diseño del diagrama organizacional asociado con el nodo actual. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Devuelve o establece el tipo de diseño del diagrama organizacional asociado con el nodo actual. |
| [remove()](#remove--) | Elimina el nodo actual. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Devuelve colecciones de todos los nodos hijos del nodo actual. Solo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Devuelve:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Devuelve colecciones de todas las formas asociadas al nodo. Solo lectura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Devuelve:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Devuelve el marco de texto del nodo. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Devuelve:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Devuelve el nivel de anidamiento del nodo. Solo lectura int.

**Devuelve:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para la viñeta de un nodo. Nota: puede devolver null para ciertos tipos de diseño SmartArt que no proporcionan viñetas para los nodos. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Devuelve true si este nodo es un nodo oculto en el modelo de datos. Solo lectura boolean.

**Devuelve:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Devuelve o establece el tipo de diseño del diagrama organizacional asociado con el nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Devuelve:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Devuelve o establece el tipo de diseño del diagrama organizacional asociado con el nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Elimina el nodo actual.

**Devuelve:**
boolean - true si se eliminó correctamente, de lo contrario false