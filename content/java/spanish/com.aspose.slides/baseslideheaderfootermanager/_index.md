---
title: BaseSlideHeaderFooterManager
second_title: Referencia de API de Aspose.Slides para Java
description: Representa el administrador que contiene el comportamiento de los marcadores de posición de pie de página, fecha y hora, número de página para todos los tipos de diapositiva.
type: docs
url: /es/com.aspose.slides/baseslideheaderfootermanager/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

Representa el administrador que contiene el comportamiento de los marcadores de posición de pie de página, fecha y hora, número de página para todos los tipos de diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gets value indicating that a footer placeholder is present. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gets value indicating that a page number placeholder is present. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gets value indicating that a date-time placeholder is present. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Changes slide footer placeholder visibility. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Changes slide page number placeholder visibility. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Changes slide date-time placeholder visibility. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sets text to slide footer placeholder. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sets text to slide date-time placeholder. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Obtiene el valor que indica que hay un marcador de posición de pie de página. Lee boolean.

**Devuelve:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Obtiene el valor que indica que hay un marcador de posición de número de página. Lee boolean.

**Devuelve:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Obtiene el valor que indica que hay un marcador de posición de fecha y hora. Lee boolean.

**Devuelve:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición del pie de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de posición del pie de página, de lo contrario lo oculta. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición del número de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de posición del número de página, de lo contrario lo oculta. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición de fecha y hora de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace visible el marcador de posición de fecha y hora, de lo contrario lo oculta. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Establece el texto del marcador de posición del pie de página de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Establece el texto del marcador de posición de fecha y hora de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |