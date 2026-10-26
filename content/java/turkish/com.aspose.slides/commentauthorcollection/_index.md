---
title: CommentAuthorCollection
second_title: Aspose.Slides için Java API Referansı
description: Yorum yazarlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/commentauthorcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Yorum yazarlarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Koleksiyonun sonuna yeni yazar ekler. |
| [toArray()](#toArray--) | Tüm yazarları içeren bir dizi oluşturur ve döndürür. |
| [findByName(String name)](#findByName-java.lang.String-) | Bir koleksiyonda adıyla yazar bulur. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Bir koleksiyonda adı ve baş harfleriyle yazar bulur. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen dizindeki yazarı kaldırır. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Koleksiyonda belirtilen yazarın ilk örneğini kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm yazarları kaldırır. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir Enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Belirtilen dizindeki öğeyi alır. Salt okunur [ICommentAuthor](../../com.aspose.slides/icommentauthor).

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


Koleksiyonun sonuna yeni yazar ekler.

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
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) dizisi
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


Bir koleksiyonda adıyla yazar bulur.

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


Bir koleksiyonda adı ve baş harfleriyle yazar bulur.

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


Koleksiyonda belirtilen dizindeki yazarı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Koleksiyonda belirtilen yazarın ilk örneğini kaldırır.

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


Koleksiyon üzerinde yineleme yapan bir Enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

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


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object