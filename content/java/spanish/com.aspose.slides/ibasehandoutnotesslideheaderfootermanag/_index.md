---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Referencia de API de Aspose.Slides para Java
description: Representa al gestor que mantiene el comportamiento de los marcadores de posición, incluido el marcador de posición de encabezado para todos los tipos de diapositivas de distribución y notas.
type: docs
url: /es/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Representa al gestor que mantiene el comportamiento de los marcadores de posición, incluido el marcador de posición de encabezado para todos los tipos de diapositivas de distribución y notas.

--------------------

El nombre original de la interfaz "IBaseHandoutNotesSlideHeaderFooterManager" se trunca a "IBaseHandoutNotesSlideHeaderFooterManag" para compatibilidad COM (la longitud del nombre del tipo no debe ser superior a 39).
## Métodos

| Método | Descripción |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtiene el valor que indica que hay un marcador de posición de encabezado. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Cambia la visibilidad del marcador de posición de encabezado de la diapositiva. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Establece el texto del marcador de posición de encabezado de la diapositiva. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Obtiene el valor que indica que hay un marcador de posición de encabezado. Lee boolean.

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
| isVisible | boolean | true - hace visible el marcador de posición de encabezado, de lo contrario - lo oculta. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Establece el texto del marcador de posición de encabezado de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |