---
title: ISmartArt
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un diagrama SmartArt.
type: docs
url: /es/com.aspose.slides/ismartart/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Representa un diagrama SmartArt.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Devuelve colecciones de todos los nodos en el objeto SmartArt. |
| [getNodes()](#getNodes--) | Devuelve colecciones de los nodos raíz en el objeto SmartArt. |
| [getLayout()](#getLayout--) | Devuelve o establece el diseño del objeto SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Devuelve o establece el diseño del objeto SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Devuelve o establece el estilo rápido del objeto SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Devuelve o establece el estilo rápido del objeto SmartArt. |
| [getColorStyle()](#getColorStyle--) | Devuelve o establece el estilo de color del objeto SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Devuelve o establece el estilo de color del objeto SmartArt. |
| [isReversed()](#isReversed--) | Devuelve o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. |
| [setReversed(boolean value)](#setReversed-boolean-) | Devuelve o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Devuelve colecciones de todos los nodos en el objeto SmartArt. Solo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Devuelve:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Devuelve colecciones de los nodos raíz en el objeto SmartArt. Solo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Devuelve:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Devuelve o establece el diseño del objeto SmartArt. Lectura/escritura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Devuelve:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Devuelve o establece el diseño del objeto SmartArt. Lectura/escritura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Devuelve o establece el estilo rápido del objeto SmartArt. Lectura/escritura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Devuelve:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Devuelve o establece el estilo rápido del objeto SmartArt. Lectura/escritura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Devuelve o establece el estilo de color del objeto SmartArt. Lectura/escritura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Devuelve:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Devuelve o establece el estilo de color del objeto SmartArt. Lectura/escritura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Devuelve o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. Lectura/escritura boolean.

**Devuelve:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Devuelve o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |