---
title: CommentCollection
second_title: Aspose.Slides için Java API Referansı
description: Bir yazarın yorumlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/commentcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Bir yazarın yorumlarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Koleksiyonun sonuna yeni yorum ekler. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Koleksiyonun sonuna yeni modern yorum ekler. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Belirtilen indeksteki koleksiyona yeni yorum ekler. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Belirtilen indeksteki koleksiyona yeni modern yorum ekler. |
| [toArray()](#toArray--) | Tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm yorumları kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Koleksiyonda indekse göre bir yorum bulur. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt okunur  int .

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt okunur [Comment](../../com.aspose.slides/comment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Koleksiyonun sonuna yeni yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni bir yorumun ekleneceği sunumdaki slayt. |
| position | java.awt.geom.Point2D.Float | Yeni bir yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Koleksiyonun sonuna yeni modern yorum ekler.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkilendirildiği slayttaki şekil. |
| position | java.awt.geom.Point2D.Float | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yeni modern yorumun oluşturulma zamanı. |

**Döndürür:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eklenen modern yorum.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Belirtilen indeksteki koleksiyona yeni yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yorumun ekleneceği koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni bir yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni bir yorumun ekleneceği sunumdaki slayt. |
| position | java.awt.geom.Point2D.Float | Yeni bir yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Belirtilen indeksteki koleksiyona yeni modern yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Modern yorumun ekleneceği koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkilendirildiği slayttaki şekil. |
| position | java.awt.geom.Point2D.Float | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yeni modern yorumun oluşturulma zamanı. |

**Döndürür:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eklenen modern yorum.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Tüm yorumları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) dizisi.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Döndürülecek ilk yorumun indeksi. |
| count | int | Döndürülecek yorum sayısı. |

**Döndürür:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) dizisi.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Koleksiyondan kaldırılacak yorum. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm yorumları kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Koleksiyon içinde yineleme için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Tüm koleksiyon için bir java.util.Iterator.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Koleksiyonda indekse göre bir yorum bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Bulunacak yorumun benzersiz indeksi  int . |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Bulunan yorum veya null [IComment](../../com.aspose.slides/icomment).
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

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur  boolean .

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur  Object .

**Döndürür:**
java.lang.Object