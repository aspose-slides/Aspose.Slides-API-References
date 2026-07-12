---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un administrador que mantiene el comportamiento de los marcadores de posición, incluido el marcador de posición de encabezado para todos los tipos de diapositivas de folleto y notas.
type: docs
url: /es/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Representa un administrador que mantiene el comportamiento de los marcadores de posición, incluido el marcador de posición de encabezado para todos los tipos de diapositivas de folletos y notas.

--------------------

El nombre original de la interfaz "IBaseHandoutNotesSlideHeaderFooterManager" se trunca a "IBaseHandoutNotesSlideHeaderFooterManag" para compatibilidad con COM (la longitud del nombre del tipo no debe ser superior a 39).
## Métodos

| Método | Descripción |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtiene el valor que indica que hay un marcador de posición de encabezado presente. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Cambia la visibilidad del marcador de posición de encabezado de la diapositiva. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Establece el texto del marcador de posición de encabezado. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Obtiene el valor que indica que hay un marcador de posición de encabezado presente. Lee boolean.

**Devuelve:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Cambia la visibilidad del marcador de posición de encabezado de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que un marcador de posición de encabezado sea visible, de lo contrario lo oculta. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Establece el texto del marcador de posición de encabezado de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |