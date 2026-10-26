---
title: CommentAuthorCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Yorum yazarlarından oluşan bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/commentauthorcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Yorum yazarlarından oluşan bir koleksiyonu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğelerin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Koleksiyonun sonuna yeni bir yazar ekler. |
| [toArray()](#toArray--) | Tüm yazarları içeren bir dizi oluşturur ve döndürür. |
| [findByName(String name)](#findByName-java.lang.String-) | İsim ile bir koleksiyondaki yazarı bulur. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | İsim ve baş harfleriyle bir koleksiyondaki yazarı bulur. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki yazarı kaldırır. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Koleksiyonda belirtilen yazarın ilk görünümünü kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm yazarları kaldırır. |
| [iterator()](#iterator--) | Koleksiyonun içinde dolaşan bir yineleyici döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir eşzamanlama kökü döndürür. |
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekten bulunan öğelerin sayısını alır. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
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
public final ICommentAuthor addAuthor(String name, String initials)
```


Koleksiyonun sonuna yeni bir yazar ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Yeni bir yazarın adı. |
| initials | java.lang.String | Yeni bir yazarın baş harfleri. |

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Yeni [ICommentAuthor](../../com.aspose.slides/icommentauthor) nesnesi.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Tüm yazarları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - Dizisi [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


İsim ile bir koleksiyondaki yazarı bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak yazarın adı. |

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - Yazar veya null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


İsim ve baş harfleriyle bir koleksiyondaki yazarı bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak yazarın adı. |
| initials | java.lang.String | Bulunacak yazarın baş harfleri. |

**Döndürür:**
com.aspose.slides.ICommentAuthor[] - Yazar veya null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyonda belirtilen indeksteki yazarı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Koleksiyonda belirtilen yazarın ilk görünümünü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Koleksiyondan kaldırılacak yazar. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondan tüm yazarları kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Koleksiyonun içinde dolaşan bir yineleyici döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Koleksiyon içinde dolaşmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir eşzamanlama kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object