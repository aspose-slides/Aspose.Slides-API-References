---
title: IBaseSlideHeaderFooterManager
second_title: Referencia de API de Aspose.Slides para Java
description: Representa el gestor que contiene el comportamiento de los marcadores de posición de pie de página, fecha y hora, y número de página para todos los tipos de diapositiva.
type: docs
url: /es/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Representa el gestor que contiene el comportamiento de los marcadores de pie de página, fecha y hora, y número de página para todos los tipos de diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Obtiene el valor que indica que existe un marcador de pie de página. Lectura booleana. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Obtiene el valor que indica que existe un marcador de número de página. Lectura booleana. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Obtiene el valor que indica que existe un marcador de fecha y hora. Lectura booleana. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Cambia la visibilidad del marcador de pie de página de la diapositiva. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Cambia la visibilidad del marcador de número de página de la diapositiva. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Cambia la visibilidad del marcador de fecha y hora de la diapositiva. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Establece el texto en el marcador de pie de página de la diapositiva. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Establece el texto en el marcador de fecha y hora de la diapositiva. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Obtiene el valor que indica que existe un marcador de pie de página. Lectura booleana.

**Devuelve:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Obtiene el valor que indica que existe un marcador de número de página. Lectura booleana.

**Devuelve:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Obtiene el valor que indica que existe un marcador de fecha y hora. Lectura booleana.

**Devuelve:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de pie de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de pie de página, de lo contrario lo oculta. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de número de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de número de página, de lo contrario lo oculta. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de fecha y hora de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de fecha y hora, de lo contrario lo oculta. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Establece el texto en el marcador de pie de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Establece el texto en el marcador de fecha y hora de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |