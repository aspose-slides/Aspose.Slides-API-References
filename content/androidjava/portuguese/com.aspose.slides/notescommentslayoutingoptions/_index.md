---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam a aparência do layout de notas e comentários no documento exportado.
type: docs
url: /pt/com.aspose.slides/notescommentslayoutingoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Fornece opções que controlam a aparência do layout de notas e comentários no documento exportado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Construtor padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Obtém ou define a visibilidade dos comentários que não têm autor. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Obtém ou define a visibilidade dos comentários que não têm autor. |
| [getNotesPosition()](#getNotesPosition--) | Obtém ou define a posição das notas na página. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Obtém ou define a posição das notas na página. |
| [getCommentsPosition()](#getCommentsPosition--) | Obtém ou define a posição dos comentários na página. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Obtém ou define a posição dos comentários na página. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Obtém ou define a cor da área de comentários (Aplicável apenas se os comentários forem exibidos à direita). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Obtém ou define a cor da área de comentários (Aplicável apenas se os comentários forem exibidos à direita). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Obtém ou define a largura da área de saída de comentários em pixels (Aplicável apenas se os comentários forem exibidos à direita). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Obtém ou define a largura da área de saída de comentários em pixels (Aplicável apenas se os comentários forem exibidos à direita). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Construtor padrão.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Obtém ou define a visibilidade dos comentários que não têm autor. Se verdadeiro, os comentários serão exibidos. (Aplicável apenas se os comentários forem exibidos).

--------------------

O valor padrão é **false**.

**Retorna:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Obtém ou define a visibilidade dos comentários que não têm autor. Se verdadeiro, os comentários serão exibidos. (Aplicável apenas se os comentários forem exibidos).

--------------------

O valor padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Obtém ou define a posição das notas na página.

--------------------

O padrão é **NotesPositions.None**.

**Retorna:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Obtém ou define a posição das notas na página.

--------------------

O padrão é **NotesPositions.None**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Obtém ou define a posição dos comentários na página.

--------------------

O padrão é **CommentsPositions.None**.

**Retorna:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Obtém ou define a posição dos comentários na página.

--------------------

O padrão é **CommentsPositions.None**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Obtém ou define a cor da área de comentários (Aplicável apenas se os comentários forem exibidos à direita).

--------------------

O padrão é **SkyBlue**.

**Retorna:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Obtém ou define a cor da área de comentários (Aplicável apenas se os comentários forem exibidos à direita).

--------------------

O padrão é **SkyBlue**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Obtém ou define a largura da área de saída de comentários em pixels (Aplicável apenas se os comentários forem exibidos à direita).

--------------------

O valor mínimo e padrão é **150**.

**Retorna:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Obtém ou define a largura da área de saída de comentários em pixels (Aplicável apenas se os comentários forem exibidos à direita).

--------------------

O valor mínimo e padrão é **150**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |