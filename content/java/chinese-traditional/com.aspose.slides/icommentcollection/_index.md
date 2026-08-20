---
title: ICommentCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示單一作者的評論集合。
type: docs
url: /zh-hant/com.aspose.slides/icommentcollection/
---
**所有已实现的接口:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

表示單一作者的評論集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的末尾新增註釋。 |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在集合的末尾新增現代註釋。 |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | 在指定索引處向集合插入新註釋。 |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | 在指定索引處向集合插入新現代註釋。 |
| [toArray()](#toArray--) | 建立並回傳包含所有註釋的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並回傳指定範圍內所有註釋的陣列。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 移除集合中指定註釋的首次出現。 |
| [clear()](#clear--) | 移除集合中的所有註釋。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

取得指定索引處的元素。唯讀 [IComment](../../com.aspose.slides/icomment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在集合的末尾新增註釋。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新註釋的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在簡報中要加入新註釋的投影片。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增註釋的位置。 |
| creationTime | java.util.Date | 註釋建立的時間。 |

**返回值:**
[IComment](../../com.aspose.slides/icomment) - 已新增的註釋。
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在集合的末尾新增現代註釋。

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
| text | java.lang.String | 新現代註釋的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在簡報中要加入新現代註釋的投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代註釋關聯的投影片形狀。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增現代註釋的位置。 |
| creationTime | java.util.Date | 新現代註釋建立的時間。 |

**返回值:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已新增的現代註釋。
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

在指定索引處向集合插入新註釋。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中要插入註釋的元素索引。 |
| text | java.lang.String | 新註釋的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在簡報中要加入新註釋的投影片。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增註釋的位置。 |
| creationTime | java.util.Date | 註釋建立的時間。 |

**返回值:**
[IComment](../../com.aspose.slides/icomment) - 已插入的註釋。
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

在指定索引處向集合插入新現代註釋。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中要插入現代註釋的元素索引。 |
| text | java.lang.String | 新現代註釋的純文字。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 在簡報中要加入新現代註釋的投影片。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 與新現代註釋關聯的投影片形狀。 |
| position | java.awt.geom.Point2D.Float | 在投影片上新增現代註釋的位置。 |
| creationTime | java.util.Date | 現代註釋建立的時間。 |

**返回值:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 已插入的現代註釋。
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

建立並回傳包含所有註釋的陣列。

**返回值:**
com.aspose.slides.IComment[] - 包含 [IComment](../../com.aspose.slides/icomment) 的陣列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

建立並回傳指定範圍內所有註釋的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 要回傳的第一個註釋的索引。 |
| count | int | 要回傳的註釋數量。 |

**返回值:**
com.aspose.slides.IComment[] - 包含 [IComment](../../com.aspose.slides/icomment) 的陣列。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

移除集合中指定註釋的首次出現。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 要從集合中移除的註釋。 |
### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有註釋。