---
title: ISlideText
second_title: Aspose.Slides para Android mediante la API de Java
description: Representa el texto extraído de la diapositiva
type: docs
url: /es/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Representa el texto extraído de la diapositiva
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | El texto en las formas de la diapositiva |
| [getMasterText()](#getMasterText--) | El texto en las formas de la página maestra para esta diapositiva |
| [getLayoutText()](#getLayoutText--) | El texto en las formas de la página de diseño para esta diapositiva |
| [getNotesText()](#getNotesText--) | El texto en las formas de la página de notas para esta diapositiva |
| [getCommentsText()](#getCommentsText--) | El texto de los comentarios de la diapositiva |
### getText() {#getText--}
```
public abstract String getText()
```

El texto en las formas de la diapositiva

**Devuelve:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

El texto en las formas de la página maestra para esta diapositiva

**Devuelve:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

El texto en las formas de la página de diseño para esta diapositiva

**Devuelve:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

El texto en las formas de la página de notas para esta diapositiva

**Devuelve:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

El texto de los comentarios de la diapositiva

--------------------

Este campo está vacío cuando el texto se extrae usando el modo Arranged.

**Devuelve:**
java.lang.String