---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /pt/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Representa um autor de comentários.
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Retorna ou define o nome do autor. |
| [setName(String value)](#setName-java.lang.String-) | Retorna ou define o nome do autor. |
| [getInitials()](#getInitials--) | Retorna ou define as iniciais do autor. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Retorna ou define as iniciais do autor. |
| [getComments()](#getComments--) | Retorna a coleção de comentários feitos por este autor. |
| [remove()](#remove--) | Remove o autor da coleção pai. |
### getName() {#getName--}
```
public abstract String getName()
```


Retorna ou define o nome do autor. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Retorna ou define o nome do autor. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Retorna ou define as iniciais do autor. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Retorna ou define as iniciais do autor. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Retorna a coleção de comentários feitos por este autor. Somente leitura [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Retorna:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Remove o autor da coleção pai.