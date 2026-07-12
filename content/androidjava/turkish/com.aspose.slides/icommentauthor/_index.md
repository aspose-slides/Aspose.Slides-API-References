---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Yorumların bir yazarını temsil eder.
type: docs
url: /tr/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Yorumların bir yazarını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Yazarın adını döndürür ya da ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Yazarın adını döndürür ya da ayarlar. |
| [getInitials()](#getInitials--) | Yazarın baş harflerini döndürür ya da ayarlar. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Yazarın baş harflerini döndürür ya da ayarlar. |
| [getComments()](#getComments--) | Bu yazar tarafından yapılan yorumların koleksiyonunu döndürür. |
| [remove()](#remove--) | Yazarı üst koleksiyondan kaldırır. |
### getName() {#getName--}
```
public abstract String getName()
```

Yazarın adını döndürür ya da ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Yazarın adını döndürür ya da ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Yazarın baş harflerini döndürür ya da ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Yazarın baş harflerini döndürür ya da ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Bu yazar tarafından yapılan yorumların koleksiyonunu döndürür. Sadece okuma [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Döndürür:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Yazarı üst koleksiyondan kaldırır.