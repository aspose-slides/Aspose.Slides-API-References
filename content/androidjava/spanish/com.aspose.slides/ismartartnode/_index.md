---  
title: ISmartArtNode  
second_title: Aspose.Slides for Android via Java API Reference  
description: Representa un nodo de un diagrama SmartArt.  
type: docs  
url: /es/com.aspose.slides/ismartartnode/  
---```
public interface ISmartArtNode
```

Representa un nodo de un diagrama SmartArt.  
## Métodos

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Devuelve colecciones de todos los nodos hijos del nodo actual. |
| [getShapes()](#getShapes--) | Devuelve colecciones de todas las formas asociadas al nodo. |
| [getTextFrame()](#getTextFrame--) | Devuelve o establece el texto del nodo. |
| [isAssistant()](#isAssistant--) | Devuelve o establece el nodo como asistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Devuelve o establece el nodo como asistente. |
| [getLevel()](#getLevel--) | Devuelve el nivel de anidación del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para la viñeta de un nodo. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [setPosition(int value)](#setPosition-int-) | Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. |
| [isHidden()](#isHidden--) | Devuelve true si este nodo es un nodo oculto en el modelo de datos. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Devuelve o establece el tipo de diseño del organigrama asociado al nodo actual. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Devuelve o establece el tipo de diseño del organigrama asociado al nodo actual. |
| [remove()](#remove--) | Elimina el nodo actual. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Devuelve colecciones de todos los nodos hijos del nodo actual. Solo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Devuelve colecciones de todas las formas asociadas al nodo. Solo lectura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Devuelve o establece el texto del nodo. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Returns:**  
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Devuelve o establece el nodo como asistente. Lectura/escritura boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Devuelve el nivel de anidación del nodo. Solo lectura int.

**Returns:**  
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para la viñeta de un nodo. Nota: puede devolver null para ciertos tipos de diseño SmartArt que no proporcionan viñetas para los nodos. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Returns:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Devuelve o establece la posición basada en cero del nodo entre los nodos hermanos. Lectura/escritura int.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Devuelve true si este nodo es un nodo oculto en el modelo de datos. Solo lectura boolean.

**Returns:**  
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Devuelve o establece el tipo de diseño del organigrama asociado al nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**  
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Devuelve o establece el tipo de diseño del organigrama asociado al nodo actual. Lectura/escritura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Elimina el nodo actual.

**Returns:**  
boolean - true if removed succesfully, otherwise false.