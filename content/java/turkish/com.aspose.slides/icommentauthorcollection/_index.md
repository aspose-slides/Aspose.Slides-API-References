---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Java API Referansı
description: Yorum yazarlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icommentauthorcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Yorum yazarlarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Koleksiyonun sonuna yeni yazar ekler. |
| [toArray()](#toArray--) | Tüm yazarları içeren bir dizi oluşturur ve döndürür. |
| [findByName(String name)](#findByName-java.lang.String-) | Koleksiyonda adıyla yazar bulur. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Koleksiyonda adı ve baş harfleriyle yazar bulur. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki yazarı kaldırır. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Koleksiyonda belirtilen yazarın ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm yazarları kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt okunur [ICommentAuthor](../../com.aspose.slides/icommentauthor).

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

Koleksiyonun sonuna yeni yazar ekler.

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

Koleksiyonda adıyla yazar bulur.

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

Koleksiyonda adı ve baş harfleriyle yazar bulur.

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

Koleksiyonda belirtilen indeksteki yazarı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Koleksiyonda belirtilen yazarın ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Koleksiyondan kaldırılacak yazar. |
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm yazarları kaldırır.