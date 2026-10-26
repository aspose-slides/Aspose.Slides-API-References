---
title: NotesCommentsLayoutingOptions
second_title: Referencia de la API de Aspose.Slides para Java
description: Proporciona opciones que controlan la apariencia del diseño de notas y comentarios en el documento exportado.
type: docs
url: /es/com.aspose.slides/notescommentslayoutingoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Proporciona opciones que controlan la apariencia del diseño de notas y comentarios en el documento exportado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Constructor predeterminado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Obtiene o establece la visibilidad de los comentarios que no tienen autor. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Obtiene o establece la visibilidad de los comentarios que no tienen autor. |
| [getNotesPosition()](#getNotesPosition--) | Obtiene o establece la posición de las notas en la página. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Obtiene o establece la posición de las notas en la página. |
| [getCommentsPosition()](#getCommentsPosition--) | Obtiene o establece la posición de los comentarios en la página. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Obtiene o establece la posición de los comentarios en la página. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Obtiene o establece el color del área de comentarios (Se aplica solo si los comentarios se muestran a la derecha). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Obtiene o establece el color del área de comentarios (Se aplica solo si los comentarios se muestran a la derecha). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Obtiene o establece el ancho del área de salida de comentarios en píxeles (Se aplica solo si los comentarios se muestran a la derecha). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Obtiene o establece el ancho del área de salida de comentarios en píxeles (Se aplica solo si los comentarios se muestran a la derecha). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Constructor predeterminado.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Obtiene o establece la visibilidad de los comentarios que no tienen autor. Si es true entonces los comentarios se mostrarán. (Se aplica solo si los comentarios se muestran).

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Obtiene o establece la visibilidad de los comentarios que no tienen autor. Si es true entonces los comentarios se mostrarán. (Se aplica solo si los comentarios se muestran).

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Obtiene o establece la posición de las notas en la página.

--------------------

El valor predeterminado es **NotesPositions.None**.

**Devuelve:**
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Obtiene o establece la posición de las notas en la página.

--------------------

El valor predeterminado es **NotesPositions.None**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Obtiene o establece la posición de los comentarios en la página.

--------------------

El valor predeterminado es **CommentsPositions.None**.

**Devuelve:**
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Obtiene o establece la posición de los comentarios en la página.

--------------------

El valor predeterminado es **CommentsPositions.None**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Obtiene o establece el color del área de comentarios (Se aplica solo si los comentarios se muestran a la derecha).

--------------------

El valor predeterminado es **Color.SkyBlue**.

**Devuelve:**
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Obtiene o establece el color del área de comentarios (Se aplica solo si los comentarios se muestran a la derecha).

--------------------

El valor predeterminado es **Color.SkyBlue**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Obtiene o establece el ancho del área de salida de comentarios en píxeles (Se aplica solo si los comentarios se muestran a la derecha).

--------------------

El valor mínimo y predeterminado es **150**.

**Devuelve:**
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Obtiene o establece el ancho del área de salida de comentarios en píxeles (Se aplica solo si los comentarios se muestran a la derecha).

--------------------

El valor mínimo y predeterminado es **150**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |