---
title: ISmartArt
second_title: Aspose.Slides para Android a través de la referencia de API Java
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
| [getNodes()](#getNodes--) | Devuelve colecciones de nodos raíz en el objeto SmartArt. |
| [getLayout()](#getLayout--) | Obtiene o establece el diseño del objeto SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Obtiene o establece el diseño del objeto SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Obtiene o establece el estilo rápido del objeto SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Obtiene o establece el estilo rápido del objeto SmartArt. |
| [getColorStyle()](#getColorStyle--) | Obtiene o establece el estilo de color del objeto SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Obtiene o establece el estilo de color del objeto SmartArt. |
| [isReversed()](#isReversed--) | Obtiene o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. |
| [setReversed(boolean value)](#setReversed-boolean-) | Obtiene o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. |
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


Devuelve colecciones de nodos raíz en el objeto SmartArt. Solo lectura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Devuelve:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Obtiene o establece el diseño del objeto SmartArt. Lectura/escritura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Devuelve:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Obtiene o establece el diseño del objeto SmartArt. Lectura/escritura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Obtiene o establece el estilo rápido del objeto SmartArt. Lectura/escritura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Devuelve:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Obtiene o establece el estilo rápido del objeto SmartArt. Lectura/escritura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Obtiene o establece el estilo de color del objeto SmartArt. Lectura/escritura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Devuelve:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Obtiene o establece el estilo de color del objeto SmartArt. Lectura/escritura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Obtiene o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. Lectura/escritura boolean.

**Devuelve:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Obtiene o establece el estado del diagrama SmartArt respecto a (de izquierda a derecha) LTR o (de derecha a izquierda) RTL, si el diagrama admite inversión. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |