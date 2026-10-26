---
title: CommentCollection
second_title: Aspose.Slides 用于 Android 的 Java API 参考
description: 表示单个作者的评论集合。
type: docs
url: /zh/com.aspose.slides/commentcollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

表示单个作者的评论集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在集合末尾添加新评论。 |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在集合末尾添加新现代评论。 |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 在集合的指定索引处插入新评论。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 在集合的指定索引处插入新现代评论。 |
| [toArray()](#toArray--) | 创建并返回包含所有评论的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回指定范围内所有评论的数组。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 删除集合中首次出现的指定评论。 |
| [clear()](#clear--) | 删除集合中的所有评论。 |
| [iterator()](#iterator--) | 返回用于遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | 按索引在集合中查找评论。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```


获取集合中实际包含的元素数量。只读  int 。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


获取指定索引处的元素。只读 [Comment](../../com.aspose.slides/comment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


在集合末尾添加新评论。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上添加新评论的演示文稿幻灯片。 |
| position | android.graphics.PointF | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回：**
[IComment](../../com.aspose.slides/icomment) - 已添加的评论。
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
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
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
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
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
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
public final IComment[] toArray()
```

Creates and returns an array with all comments.

**Returns:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Creates and returns an array with all comments from the specified range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first comment to return. |
| count | int | A number of comments to return. |

**Returns:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the element at the specified index in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Removes the first occurrence of the specified comment in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | The comment to remove from a collection. |

### clear() {#clear--}
```
public final void clear()
```
删除集合中的所有评论。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - An java.util.Iterator for the entire collection.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Finds a comment in the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| idx | int | Unique index of a comment to find  int . |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Found comment or null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()


返回一个同步根。只读  Object 。

**返回：**
java.lang.Object
