---
title: CommentCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir yazarın yorum koleksiyonunu temsil eder.
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

Bir yazarın yorum koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan öğe sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Koleksiyonun sonuna yeni yorum ekler. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Koleksiyonun sonuna yeni modern yorum ekler. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Belirtilen indekste koleksiyona yeni yorum ekler. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Belirtilen indekste koleksiyona yeni modern yorum ekler. |
| [toArray()](#toArray--) | Tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm yorumları kaldırır. |
| [iterator()](#iterator--) | Koleksiyonun içinde dolaşan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Koleksiyonda index ile bir yorum bulur. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan öğe sayısını alır. Yalnızca okunabilir int .

**Döndürür:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okunabilir [Comment](../../com.aspose.slides/comment).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Koleksiyonun sonuna yeni yorum ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni yorumun ekleneceği sunumdaki slayt. |
| position | android.graphics.PointF | Yeni yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Koleksiyonun sonuna yeni modern yorum ekler.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkilendirildiği slayttaki şekil. |
| position | android.graphics.PointF | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Modern yorumun oluşturulma zamanı. |

**Döndürür:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eklenen modern yorum.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Belirtilen indekste koleksiyona yeni yorum ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Yorumun eklenmesi gereken koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni bir yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni yorumun ekleneceği sunumdaki slayt. |
| position | android.graphics.PointF | Yeni yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Belirtilen indekste koleksiyona yeni modern yorum ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Modern yorumun eklenmesi gereken koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni bir modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkilendirildiği slayttaki şekil. |
| position | android.graphics.PointF | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | java.util.Date | Modern yorumun oluşturulma zamanı. |

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
| Parametre | Tip | Açıklama |
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
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

Koleksiyon içinde dolaşan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Koleksiyon içinde dolaşmak için kullanılabilecek bir IGenericEnumerator.

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

Koleksiyonda index ile bir yorum bulur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| idx | int | Bulunacak yorumun benzersiz indeksi int. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Bulunan yorum veya null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object