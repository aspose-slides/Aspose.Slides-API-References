---
title: CommentCollection
second_title: Aspose.Slides for Java API 參考
description: 表示單一作者的評論集合。
type: docs
url: /zh-hant/com.aspose.slides/commentcollection/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

表示單一作者的評論集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾新增評論。 |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾新增現代評論。 |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的指定索引插入新評論。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的指定索引插入新現代評論。 |
| [toArray()](#toArray--) | 建立並傳回包含所有評論的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回指定範圍內所有評論的陣列。 |
| [removeAt(int index)](#removeAt-int-) | 刪除集合中指定索引處的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 刪除集合中指定評論的第一次出現。 |
| [clear()](#clear--) | 刪除集合中所有評論。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | 依索引在集合中尋找評論。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。唯讀  int 。

**返回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

取得指定索引處的元素。唯讀 [Comment](../../com.aspose.slides/comment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合末尾新增評論。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其中新增新評論的投影片。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增評論的位置。 |
| creationTime | java.util.Date | 評論建立的時間。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已新增的評論。
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合末尾新增現代評論。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其中新增新現代評論的投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片形狀。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增現代評論的位置。 |
| creationTime | java.util.Date | 現代評論建立的時間。 |

**返回:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已新增的現代評論。
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合的指定索引插入新評論。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要在集合中插入評論的元素索引。 |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其中新增新評論的投影片。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增評論的位置。 |
| creationTime | java.util.Date | 評論建立的時間。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已插入的評論。
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合的指定索引插入新現代評論。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 在集合中插入現代評論的元素索引。 |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其中新增新現代評論的投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片形狀。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增現代評論的位置。 |
| creationTime | java.util.Date | 現代評論建立的時間。 |

**返回:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的現代評論。
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

建立並傳回包含所有評論的陣列。

**返回:**
com.aspose.slides.IComment[] - 陣列，元素為 [Comment](../../com.aspose.slides/comment)。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

建立並傳回指定範圍內所有評論的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 要返回的第一個評論的索引。 |
| count | int | 要返回的評論數量。 |

**返回:**
com.aspose.slides.IComment[] - 陣列，元素為 [Comment](../../com.aspose.slides/comment)。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

刪除集合中指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要刪除的元素的零基索引。 |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

刪除集合中指定評論的第一次出現。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要從集合中移除的評論。 |

### clear() {#clear--}
```
public final void clear()
```

刪除集合中所有評論。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

傳回用於遍歷集合的列舉器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 整個集合的 java.util.Iterator。
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

依索引在集合中尋找評論。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| idx | int | 要尋找的評論的唯一索引 int。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已找到的評論或 null [IComment](../../com.aspose.slides/icomment)。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀  boolean 。

**返回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀  Object 。

**返回:**
java.lang.Object