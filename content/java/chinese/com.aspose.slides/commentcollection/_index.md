---
title: CommentCollection
second_title: Aspose.Slides Java API 参考
description: 表示某一作者的评论集合。
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

表示某一作者的评论集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾添加新的评论。 |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾添加新的现代评论。 |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的指定索引处插入新的评论。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的指定索引处插入新的现代评论。 |
| [toArray()](#toArray--) | 创建并返回包含所有评论的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回指定范围内所有评论的数组。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 移除集合中指定评论的第一次出现。 |
| [clear()](#clear--) | 移除集合中的所有评论。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | 按索引在集合中查找评论。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

获取集合实际包含的元素数量。只读 int .

**返回:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

获取指定索引处的元素。只读 [Comment](../../com.aspose.slides/comment).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合末尾添加新的评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上添加新评论的演示文稿中的幻灯片。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已添加的评论。

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合末尾添加新的现代评论。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新现代评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上添加新现代评论的演示文稿中的幻灯片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 与新现代评论关联的幻灯片上的形状。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新现代评论的位置。 |
| creationTime | java.util.Date | 现代评论创建的时间。 |

**返回:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已添加的现代评论。

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合的指定索引处插入新的评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中应插入评论的元素索引。 |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上添加新评论的演示文稿中的幻灯片。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已插入的评论。

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合的指定索引处插入新的现代评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中应插入现代评论的元素索引。 |
| text | java.lang.String | 新现代评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要在其上添加新现代评论的演示文稿中的幻灯片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 与新现代评论关联的幻灯片上的形状。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新现代评论的位置。 |
| creationTime | java.util.Date | 现代评论创建的时间。 |

**返回:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的现代评论。

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

创建并返回包含所有评论的数组。

**返回:**
com.aspose.slides.IComment[] - 包含 [Comment](../../com.aspose.slides/comment) 的数组。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

创建并返回指定范围内所有评论的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要返回的第一个评论的索引。 |
| count | int | 要返回的评论数量。 |

**返回:**
com.aspose.slides.IComment[] - 包含 [Comment](../../com.aspose.slides/comment) 的数组。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

移除集合中指定评论的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要从集合中移除的评论。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有评论。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 整个集合的 java.util.Iterator。

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

按索引在集合中查找评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| idx | int | 要查找的评论的唯一索引 int 。 |

**返回:**
[IComment](../../com.aspose.slides/icomment) - 已找到的评论或 null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示集合访问是否同步（线程安全）的值。只读 boolean .

**返回:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object .

**返回:**
java.lang.Object