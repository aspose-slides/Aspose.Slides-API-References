---
title: Paragraph
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/paragraph/
---
## Paragraph 类

 Represents a paragraph of text.
 
### Paragraph {#Paragraph}

| 名称 | 描述 |
| --- | --- |
| Paragraph() | 使用默认属性初始化 Paragraph 类的新实例。 |

 **返回：**
Paragraph


---


### Paragraph {#Paragraph}

| 名称 | 描述 |
| --- | --- |
| Paragraph([Paragraph](../paragraph)) | 复制函数，用于初始化 Paragraph 类的新实例。 |

 **返回：**
Paragraph


---


### getEndParagraphPortionFormat {#getEndParagraphPortionFormat}

| 名称 | 描述 |
| --- | --- |
| getEndParagraphPortionFormat () | 指定如果在最后一个 portion 之后插入另一个 portion 时要使用的 portion 属性。 |

 **返回：**
[PortionFormat](../portionformat)


---


### getLinesCount {#getLinesCount}

| 名称 | 描述 |
| --- | --- |
| getLinesCount () | 获取段落中的行数。 |

 **返回：**
int


---


### getParagraphFormat {#getParagraphFormat}

| 名称 | 描述 |
| --- | --- |
| getParagraphFormat () | 返回此段落的格式化对象。只读 IParagraphFormat。该格式化对象仅包含当前段落定义的格式化参数，不会应用继承的数据。若要获取包括继承值在内的实际值，请使用 ParagraphFormat#getEffective 方法。 |

 **返回：**
[ParagraphFormat](../paragraphformat)


---


### getPortions {#getPortions}

| 名称 | 描述 |
| --- | --- |
| getPortions () | 返回文本片段的集合。只读 IPortionCollection。 |

 **返回：**
[PortionCollection](../portioncollection)


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回段落所属的父演示文稿。只读 IPresentation。 |

 **返回：**
[Presentation](../presentation)


---


### getRect {#getRect}

| 名称 | 描述 |
| --- | --- |
| getRect () | 获取限定段落的矩形坐标。该矩形包括段落中所有文本行，包括空行。 |

 **返回：**
Rectangle2D.Float


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回段落所属的父幻灯片。只读 BaseSlide。 |

 **返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| 名称 | 描述 |
| --- | --- |
| getText () | 获取或设置段落的纯文本。可读写 String。值：文本。 |

 **返回：**
String


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| 名称 | 描述 |
| --- | --- |
| joinPortionsWithSameFormatting () | 合并具有相同格式的运行。 |

 **返回：**
void


---


### setEndParagraphPortionFormat {#setEndParagraphPortionFormat}

| 名称 | 描述 |
| --- | --- |
| setEndParagraphPortionFormat ([PortionFormat](../portionformat)) | 指定如果在最后一个 portion 之后插入另一个 portion 时要使用的 portion 属性。 |

 **返回：**
void


---


### setText {#setText}

| 名称 | 描述 |
| --- | --- |
| setText (String) | 获取或设置段落的纯文本。可读写 String。值：文本。 |

 **返回：**
void


---