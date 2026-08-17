---
title: ICommentCollection
second_title: Aspose.Slides Java API 参考
description: 表示单个作者的评论集合。
type: docs
url: /zh/com.aspose.slides/icommentcollection/
---
**所有已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

表示单个作者的评论集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾添加新评论。 |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合末尾添加新现代评论。 |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在指定索引处向集合插入新评论。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在指定索引处向集合插入新现代评论。 |
| [toArray()](#toArray--) | 创建并返回包含所有评论的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回指定范围内所有评论的数组。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 移除集合中指定评论的第一次出现。 |
| [clear()](#clear--) | 移除集合中的所有评论。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

获取指定索引处的元素。只读 [IComment](../../com.aspose.slides/icomment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合末尾添加新评论。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在演示文稿中添加新评论的幻灯片。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回值：**
[IComment](../../com.aspose.slides/icomment) - 已添加的评论。
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合末尾添加新现代评论。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新现代评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在演示文稿中添加新现代评论的幻灯片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 幻灯片上与新现代评论关联的形状。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新现代评论的位置。 |
| creationTime | java.util.Date | 新现代评论创建的时间。 |

**返回值：**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已添加的现代评论。
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在指定索引处向集合插入新评论。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中插入评论的元素索引。 |
| text | java.lang.String | 新评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在演示文稿中添加新评论的幻灯片。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新评论的位置。 |
| creationTime | java.util.Date | 评论创建的时间。 |

**返回值：**
[IComment](../../com.aspose.slides/icomment) - 已插入的评论。
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在指定索引处向集合插入新现代评论。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中插入现代评论的元素索引。 |
| text | java.lang.String | 新现代评论的纯文本。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在演示文稿中添加新现代评论的幻灯片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 幻灯片上与新现代评论关联的形状。 |
| position | java.awt.geom.Point2D.Float | 在幻灯片上添加新现代评论的位置。 |
| creationTime | java.util.Date | 新现代评论创建的时间。 |

**返回值：**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的现代评论。
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

创建并返回包含所有评论的数组。

**返回值：**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) 的数组。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

创建并返回指定范围内所有评论的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要返回的第一条评论的索引。 |
| count | int | 要返回的评论数量。 |

**返回值：**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) 的数组。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

移除集合中指定评论的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要从集合中移除的评论。 |
### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有评论。