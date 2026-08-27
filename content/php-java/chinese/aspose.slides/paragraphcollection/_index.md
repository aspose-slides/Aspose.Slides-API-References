---
title: ParagraphCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/paragraphcollection/
---
## ParagraphCollection 类

 表示一组段落。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([Paragraph](../paragraph)) | 将 Paragraph 添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [Paragraph](../paragraph) | 要添加到集合末尾的 Paragraph。 |

 **返回:**
void


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([ParagraphCollection](../paragraphcollection)) | 将 ParagraphCollection 的内容添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ParagraphCollection](../paragraphcollection) | 要添加到集合末尾的 ParagraphCollection。 |

 **返回:**
int


---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String) | 将指定的 html 字符串中的文本添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | HTML 文本。 |

 **返回:**
void


---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | 将指定的 html 字符串中的文本添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | HTML 文本。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 解析 URI 并获取引用对象的解析器回调对象。 |
| uri | String | 用于添加 HTML 文档的 URI。用于解析相对链接。指定解析器可能会引入漏洞，请谨慎使用。 |

 **返回:**
void


---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | 将指定的 html 字符串中的文本添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | HTML 文本。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 解析 URI 并获取引用对象的解析器回调对象。 |
| uri | String | 用于添加 HTML 文档的 URI。用于解析相对链接。指定解析器可能会引入漏洞，请谨慎使用。 |

 **返回:**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有元素。 |

 **返回:**
void


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains ([Paragraph](../paragraph)) | 确定 IGenericCollection 是否包含特定值。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | 在 IGenericCollection 中定位的对象。 |

 **返回:**
boolean


---


### copyTo {#copyTo}

| 名称 | 描述 |
| --- | --- |
| copyTo (com.aspose.slides.IParagraph[], int) | 将 IGenericCollection 的元素复制到数组中，从特定的数组索引开始。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.slides.IParagraph[] | 一维数组，用作从 IGenericCollection 复制的元素的目标。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的数组零基索引。 |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 源 IGenericCollection 中的元素数量大于从 arrayIndex 到目标数组末尾的可用空间。 |


---


### exportToHtml {#exportToHtml}

| 名称 | 描述 |
| --- | --- |
| exportToHtml (int, int, [TextToHtmlConversionOptions](../texttohtmlconversionoptions)) | 将指定的段落转换为 HTML 并作为 String 对象返回。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| firstParagraphIndex | int | 第一个段落的索引 int |
| paragraphsCount | int | 段落数量 int |
| options | [TextToHtmlConversionOptions](../texttohtmlconversionoptions) | 转换选项 ITextToHtmlConversionOptions |

 **返回:**
String


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取集合实际包含的元素数量。只读 int。 |

 **返回:**
int


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回段落集合的父演示文稿。只读 IPresentation。 |

 **返回:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回段落集合的父幻灯片。只读 BaseSlide。 |

 **返回:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。 |

 **返回:**
[Paragraph](../paragraph)


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Paragraph](../paragraph)) | 确定 List 中特定项的索引。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | 在 List 中定位的对象。 |

 **返回:**
int


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [Paragraph](../paragraph)) | 在指定索引处将 Paragraph 插入到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | Paragraph 应插入的零基索引。 |
| value | [Paragraph](../paragraph) | 要插入的 Paragraph。 |

 **返回:**
void


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [ParagraphCollection](../paragraphcollection)) | 在指定索引处将 ParagraphCollection 的内容插入到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 段落应插入的零基索引。 |
| value | [ParagraphCollection](../paragraphcollection) | 要插入的段落。 |

 **返回:**
void


---


### isReadOnly {#isReadOnly}

| 名称 | 描述 |
| --- | --- |
| isReadOnly () | 获取指示 IGenericCollection 是否为只读的值。只读 boolean。 |

 **返回:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

 **返回:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回:**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Paragraph](../paragraph)) | 从 IGenericCollection 中移除特定对象的第一次出现。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | 从 IGenericCollection 中要移除的对象。 |

 **返回:**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | IGenericCollection 为只读。 |


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除集合中指定索引处的元素。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

 **返回:**
void


---