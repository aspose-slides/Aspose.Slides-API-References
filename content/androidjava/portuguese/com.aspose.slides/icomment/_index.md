---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Representa um comentário em um slide.
type: docs
url: /pt/com.aspose.slides/icomment/
---```
public interface IComment
```

Representa um comentário em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getText()](#getText--) | Obtém ou define o texto simples de um comentário de slide. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um comentário de slide. |
| [getCreatedTime()](#getCreatedTime--) | Obtém ou define o horário de criação de um comentário. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Obtém ou define o horário de criação de um comentário. |
| [getSlide()](#getSlide--) | Obtém ou define o slide pai de um comentário. |
| [getAuthor()](#getAuthor--) | Obtém o autor de um comentário. |
| [getPosition()](#getPosition--) | Obtém ou define a posição de um comentário em um slide. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Obtém ou define a posição de um comentário em um slide. |
| [remove()](#remove--) | Remove o comentário e todas as suas respostas da coleção pai. |
| [getParentComment()](#getParentComment--) | Obtém ou define o comentário pai. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtém ou define o comentário pai. |
### getText() {#getText--}
```
public abstract String getText()
```

Obtém ou define o texto simples de um comentário de slide. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtém ou define o texto simples de um comentário de slide. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Obtém ou define o horário de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhum horário de comentário está definido. Leitura/Gravação java.util.Date.

--------------------

O horário do comentário é um parâmetro opcional.

**Retorna:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Obtém ou define o horário de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhum horário de comentário está definido. Leitura/Gravação java.util.Date.

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
public abstract PointF getPosition()
```

Obtém ou define a posição de um comentário em um slide. Leitura/Gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Obtém ou define a posição de um comentário em um slide. Leitura/Gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Remove o comentário e todas as suas respostas da coleção pai.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Obtém ou define o comentário pai. Leitura/Gravação [IComment](../../com.aspose.slides/icomment).

**Retorna:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Obtém ou define o comentário pai. Leitura/Gravação [IComment](../../com.aspose.slides/icomment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |