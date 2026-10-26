---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Representa um comentário em um slide.
type: docs
url: /pt/com.aspose.slides/icomment/
---```
public interface IComment
```

Representa um comentário em um slide.
## Methods

| Método | Descrição |
| --- | --- |
| [getText()](#getText--) | Obtém ou define o texto simples de um comentário em um slide. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um comentário em um slide. |
| [getCreatedTime()](#getCreatedTime--) | Obtém ou define a hora de criação de um comentário. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Obtém ou define a hora de criação de um comentário. |
| [getSlide()](#getSlide--) | Obtém ou define o slide pai de um comentário. |
| [getAuthor()](#getAuthor--) | Obtém o autor de um comentário. |
| [getPosition()](#getPosition--) | Obtém ou define a posição de um comentário em um slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Obtém ou define a posição de um comentário em um slide. |
| [remove()](#remove--) | Remove o comentário e todas as suas respostas da coleção pai. |
| [getParentComment()](#getParentComment--) | Obtém ou define o comentário pai. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtém ou define o comentário pai. |
### getText() {#getText--}
```
public abstract String getText()
```


Obtém ou define o texto simples de um comentário em um slide. Leitura/gravação String.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Obtém ou define o texto simples de um comentário em um slide. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Obtém ou define a hora de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhuma hora de comentário está definida. Leitura/gravação java.util.Date.

--------------------

O horário do comentário é um parâmetro opcional.

**Retorna:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Obtém ou define a hora de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhuma hora de comentário está definida. Leitura/gravação java.util.Date.

--------------------

O horário do comentário é um parâmetro opcional.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Obtém ou define o slide pai de um comentário. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Obtém o autor de um comentário. Somente leitura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Retorna:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Obtém ou define a posição de um comentário em um slide. Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Obtém ou define a posição de um comentário em um slide. Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Remove o comentário e todas as suas respostas da coleção pai.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Obtém ou define o comentário pai. Leitura/gravação [IComment](../../com.aspose.slides/icomment).

**Retorna:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Obtém ou define o comentário pai. Leitura/gravação [IComment](../../com.aspose.slides/icomment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |