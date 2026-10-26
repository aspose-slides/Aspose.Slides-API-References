---
title: ICommentCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示某一作者的评论集合。
type: docs
url: /zh/com.aspose.slides/icommentcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

表示某一作者的评论集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在集合末尾添加新评论。 |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在集合末尾添加新现代评论。 |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在集合的指定索引处插入新评论。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在集合的指定索引处插入新现代评论。 |
| [toArray()](#toArray--) | 创建并返回包含所有评论的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有评论的数组。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 删除集合中指定评论的第一次出现。 |
| [clear()](#clear--) | 删除集合中的所有评论。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


获取指定索引处的元素。只读 [IComment](../../com.aspose.slides/icomment)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


在集合末尾添加新评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 演示文稿中要添加新评论的幻灯片。 |
| position | android.graphics.PointF | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回值:**
[IComment](../../com.aspose.slides/icomment) - 已添加的评论。
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


在集合末尾添加新现代评论。

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
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | android.graphics.PointF | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Added modern comment.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Insert new comment to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the element in a collection at which comment should be inserted. |
| text | java.lang.String | Plain text of a new comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | android.graphics.PointF | Position on a slide where to add a new comment. |
| creationTime | java.util.Date | Time of a comment creation. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Inserted comment.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Insert new modern comment to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the element in a collection at which modern comment should be inserted. |
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | android.graphics.PointF | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Inserted modern comment.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Creates and returns an array with all comments.

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Creates and returns an array with all comments from the specified range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first comment to return. |
| count | int | A number of comments to return. |

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the specified index in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Removes the first occurrence of the specified comment in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | The comment to remove from a collection. |

### clear() {#clear--}
```
public abstract void clear()


删除集合中的所有评论。