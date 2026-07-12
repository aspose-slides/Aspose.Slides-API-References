---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Yorum yazarlarından oluşan bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/icommentauthorcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Yorum yazarlarından oluşan bir koleksiyonu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Yeni bir yazarı koleksiyonun sonuna ekler. |
| [toArray()](#toArray--) | Tüm yazarları içeren bir dizi oluşturur ve döndürür. |
| [findByName(String name)](#findByName-java.lang.String-) | Bir koleksiyonda adıyla yazarı bulur. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Bir koleksiyonda adı ve baş harfleriyle yazarı bulur. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksindeki yazarı kaldırır. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Koleksiyonda belirtilen yazarın ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm yazarları kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Yalnızca okuma [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Yeni bir yazarı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Yeni yazarın adı. |
| initials | java.lang.String | Yeni yazarın baş harfleri. |

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Yeni [ICommentAuthor](../../com.aspose.slides/icommentauthor) nesnesi.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Tüm yazarları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) dizisi
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Bir koleksiyonda adıyla yazarı bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak yazarın adı. |

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - Yazar veya null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Bir koleksiyonda adı ve baş harfleriyle yazarı bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak yazarın adı. |
| initials | java.lang.String | Bulunacak yazarın baş harfleri. |

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - Yazar veya null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyonun belirtilen indeksindeki yazarı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Koleksiyondan kaldırılacak yazarın ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Koleksiyondan kaldırılacak yazar. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm yazarları kaldırır.