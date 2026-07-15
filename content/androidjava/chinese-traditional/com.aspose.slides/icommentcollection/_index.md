---
title: ICommentCollection
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示單一作者的評論集合。
type: docs
url: /zh-hant/com.aspose.slides/icommentcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

表示單一作者的評論集合。
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在集合的末端新增評論。 |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在集合的末端新增現代評論。 |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在指定索引處將新評論插入集合。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在指定索引處將新現代評論插入集合。 |
| [toArray()](#toArray--) | 建立並傳回包含所有評論的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回包含指定範圍內所有評論的陣列。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 移除集合中第一個出現的指定評論。 |
| [clear()](#clear--) | 移除集合中的所有評論。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


取得指定索引處的元素。唯讀 [IComment](../../com.aspose.slides/icomment)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


在集合的末端新增評論。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增評論的簡報投影片。 |
| position | android.graphics.PointF | 在投影片上新增評論的位置。 |
| creationTime | java.util.Date | 評論建立的時間。 |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - 已新增的評論。
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


在集合的末端新增現代評論。

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增現代評論的簡報投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片上圖形。 |
| position | android.graphics.PointF | 在投影片上新增現代評論的位置。 |
| creationTime | java.util.Date | 現代評論建立的時間。 |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已新增的現代評論。
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


在集合的指定索引處插入新評論。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入評論的集合中元素索引。 |
| text | java.lang.String | 新評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增評論的簡報投影片。 |
| position | android.graphics.PointF | 在投影片上新增評論的位置。 |
| creationTime | java.util.Date | 評論建立的時間。 |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - 已插入的評論。
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


在集合的指定索引處插入新現代評論。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入現代評論的集合中元素索引。 |
| text | java.lang.String | 新現代評論的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上新增現代評論的簡報投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代評論關聯的投影片上圖形。 |
| position | android.graphics.PointF | 在投影片上新增現代評論的位置。 |
| creationTime | java.util.Date | 現代評論建立的時間。 |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的現代評論。
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


建立並傳回包含所有評論的陣列。

**Returns:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) 陣列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


建立並傳回包含指定範圍內所有評論的陣列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 要傳回的第一筆評論的索引。 |
| count | int | 要傳回的評論數量。 |

**Returns:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) 陣列。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引處的元素。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


移除集合中第一個出現的指定評論。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要從集合中移除的評論。 |

### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有評論。