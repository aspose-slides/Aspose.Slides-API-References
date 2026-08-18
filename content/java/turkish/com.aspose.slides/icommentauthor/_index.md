---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
url: /tr/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Yorumların bir yazarını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getName()](#getName--) | Yazarın adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Yazarın adını döndürür veya ayarlar. |
| [getInitials()](#getInitials--) | Yazarın baş harflerini döndürür veya ayarlar. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Yazarın baş harflerini döndürür veya ayarlar. |
| [getComments()](#getComments--) | Bu yazar tarafından yapılan yorumların koleksiyonunu döndürür. |
| [remove()](#remove--) | Yazarı üst koleksiyondan kaldırır. |
### getName() {#getName--}
```
public abstract String getName()
```


Yazarın adını döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Yazarın adını döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Yazarın baş harflerini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Yazarın baş harflerini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Bu yazarın yaptığı yorumların koleksiyonunu döndürür. Yalnızca okunur [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Döndürür:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Yazarı üst koleksiyondan kaldırır.