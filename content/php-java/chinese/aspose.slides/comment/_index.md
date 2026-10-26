---
title: Comment
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/comment/
---
## Comment 类

 表示幻灯片上的注释。

### getAuthor {#getAuthor}

| 名称 | 描述 |
| --- | --- |
| getAuthor () | 返回注释的作者。只读 ICommentAuthor。 |

 **返回：**
[CommentAuthor](../commentauthor)

---

### getCreatedTime {#getCreatedTime}

| 名称 | 描述 |
| --- | --- |
| getCreatedTime () | 返回或设置注释创建的时间。将此属性设置为 java.util.Date(Long.MIN_VALUE) 表示未设置注释时间。可读写 java.util.Date。注释时间是可选参数。 |

 **返回：**
Date

---

### getParentComment {#getParentComment}

| 名称 | 描述 |
| --- | --- |
| getParentComment () | 获取或设置父注释。可读写 IComment。 |

 **返回：**
[Comment](../comment), [ModernComment](../moderncomment)

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当设置值导致循环引用时抛出 |

---

### getPosition {#getPosition}

| 名称 | 描述 |
| --- | --- |
| getPosition () | 返回或设置幻灯片上注释的位置。可读写 java.awt.geom.Point2D.Float。 |

 **返回：**
Point2D.Float

---

### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回或设置注释的父幻灯片。只读 ISlide。 |

 **返回：**
[Slide](../slide)

---

### getText {#getText}

| 名称 | 描述 |
| --- | --- |
| getText () | 返回或设置幻灯片注释的纯文本。可读写 String。 |

 **返回：**
String

---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove () | 从父集合中删除注释及其所有回复。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果注释已被删除则抛出 |

---

### setCreatedTime {#setCreatedTime}

| 名称 | 描述 |
| --- | --- |
| setCreatedTime (Date) | 返回或设置注释创建的时间。将此属性设置为 java.util.Date(Long.MIN_VALUE) 表示未设置注释时间。可读写 java.util.Date。注释时间是可选参数。 |

 **返回：**
void

---

### setParentComment {#setParentComment}

| 名称 | 描述 |
| --- | --- |
| setParentComment ([Comment](../comment)) | 获取或设置父注释。可读写 IComment。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当设置值导致循环引用时抛出 |

---

### setParentComment {#setParentComment}

| 名称 | 描述 |
| --- | --- |
| setParentComment ([ModernComment](../moderncomment)) | 获取或设置父注释。可读写 IComment。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当设置值导致循环引用时抛出 |

---

### setPosition {#setPosition}

| 名称 | 描述 |
| --- | --- |
| setPosition (Point2D.Float) | 返回或设置幻灯片上注释的位置。可读写 java.awt.geom.Point2D.Float。 |

 **返回：**
void

---

### setText {#setText}

| 名称 | 描述 |
| --- | --- |
| setText (String) | 返回或设置幻灯片注释的纯文本。可读写 String。 |

 **返回：**
void

---