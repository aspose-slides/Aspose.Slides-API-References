---
title: ICommentCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Tek bir yazarın yorum koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icommentcollection/
---
**Tüm Gerçekleştirilen Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Tek bir yazarın yorum koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Bir koleksiyonun sonuna yeni yorum ekler. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Bir koleksiyonun sonuna yeni modern yorum ekler. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Belirtilen indeksteki bir koleksiyona yeni yorum ekler. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Belirtilen indeksteki bir koleksiyona yeni modern yorum ekler. |
| [toArray()](#toArray--) | Tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [removeAt(int index)](#removeAt-int-) | Bir koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Bir koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Bir koleksiyondaki tüm yorumları kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Yalnızca okunabilir [IComment](../../com.aspose.slides/icomment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Bir koleksiyonun sonuna yeni yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni yorumun ekleneceği sunumdaki slayt. |
| position | android.graphics.PointF | Yeni yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Bir koleksiyonun sonuna yeni modern yorum ekler.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkili olduğu slayttaki şekil. |
| position | android.graphics.PointF | Yeni modern yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | java.util.Date | Modern yorumun oluşturulma zamanı. |

**Döndürür:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eklenen modern yorum.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Belirtilen indeksteki bir koleksiyona yeni yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yorumun ekleneceği koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni yorumun ekleneceği sunumdaki slayt. |
| position | android.graphics.PointF | Yeni yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | java.util.Date | Yorumun oluşturulma zamanı. |

**Döndürür:**
[IComment](../../com.aspose.slides/icomment) - Eklenen yorum.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Belirtilen indeksteki bir koleksiyona yeni modern yorum ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Modern yorumun ekleneceği koleksiyondaki öğenin indeksi. |
| text | java.lang.String | Yeni modern yorumun düz metni. |
| slide | [ISlide](../../com.aspose.slides/islide) | Yeni modern yorumun ekleneceği sunumdaki slayt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Yeni modern yorumun ilişkilendirildiği slayttaki şekil. |
| position | android.graphics.PointF | Yeni modern yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | java.util.Date | Modern yorumun oluşturulma zamanı. |

**Döndürür:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eklenen modern yorum.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Tüm yorumları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) dizisi.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Döndürülecek ilk yorumun indeksi. |
| count | int | Döndürülecek yorum sayısı. |

**Döndürür:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) dizisi.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Bir koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Bir koleksiyonda belirtilen yorumun ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Koleksiyondan kaldırılacak yorum. |

### clear() {#clear--}
```
public abstract void clear()
```


Bir koleksiyondaki tüm yorumları kaldırır.