---
title: CommentCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表單一作者的評論集合。
type: docs
url: /zh-hant/com.aspose.slides/commentcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

代表單一作者的評論集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Add new comment at the end of a collection. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Add new modern comment at the end of a collection. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Insert new comment to a collection at the specified index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Insert new modern comment to a collection at the specified index. |
| [toArray()](#toArray--) | Creates and returns an array with all comments. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all comments from the specified range. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index in a collection. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Removes the first occurrence of the specified comment in a collection. |
| [clear()](#clear--) | Removes all comments from a collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Finds a comment in the collection by index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。 唯讀  int .

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

取得在指定索引處的元素。 唯讀 [Comment](../../com.aspose.slides/comment)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

在集合的末尾新增評論。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增新評論的簡報投影片。 |
| position | android.graphics.PointF | 要在其上新增新評論的投影片位置。 |
| creationTime | java.util.Date | 評論的建立時間。 |

**返回：**
[IComment](../../com.aspose.slides/icomment) - 已新增的評論。
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

在集合的末尾新增現代評論。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增新現代評論的簡報投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片形狀。 |
| position | android.graphics.PointF | 要在其上新增新現代評論的投影片位置。 |
| creationTime | java.util.Date | 新現代評論的建立時間。 |

**返回：**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已新增的現代評論。
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

在集合的指定索引處插入新評論。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入評論的集合索引位置。 |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增新評論的簡報投影片。 |
| position | android.graphics.PointF | 要在其上新增新評論的投影片位置。 |
| creationTime | java.util.Date | 評論的建立時間。 |

**返回：**
[IComment](../../com.aspose.slides/icomment) - 已插入的評論。
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

在集合的指定索引處插入新現代評論。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入現代評論的集合索引位置。 |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增新現代評論的簡報投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片形狀。 |
| position | android.graphics.PointF | 要在其上新增新現代評論的投影片位置。 |
| creationTime | java.util.Date | 現代評論的建立時間。 |

**返回：**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的現代評論。
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

建立並返回包含所有評論的陣列。

**返回：**
com.aspose.slides.IComment[] - 陣列，包含 [Comment](../../com.aspose.slides/comment)。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

建立並返回指定範圍內所有評論的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 要返回的第一個評論的索引。 |
| count | int | 要返回的評論數量。 |

**返回：**
com.aspose.slides.IComment[] - 陣列，包含 [Comment](../../com.aspose.slides/comment)。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

移除集合中第一個出現的指定評論。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要從集合中移除的評論。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中全部評論。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

傳回遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 用於整個集合的 java.util.Iterator。
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

在集合中依索引尋找評論。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| idx | int | 要尋找的評論之唯一索引  int . |

**返回：**
[IComment](../../com.aspose.slides/icomment) - 找到的評論或 null [IComment](../../com.aspose.slides/icomment)。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 唯讀  boolean .

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。 唯讀  Object .

**返回：**
java.lang.Object