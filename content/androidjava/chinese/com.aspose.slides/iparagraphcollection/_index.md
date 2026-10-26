---
title: IParagraphCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示段落的集合。
type: docs
url: /zh/com.aspose.slides/iparagraphcollection/
---
**所有实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

表示段落的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getCount()](#getCount--) | 获取集合实际包含的元素数量。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 在集合末尾添加一个 Paragraph。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 在集合末尾添加 ParagraphCollection 的内容。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 在指定索引处将 Paragraph 插入集合。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 在指定索引处将 ParagraphCollection 的内容插入集合。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 移除特定段落的第一次出现。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 将指定的 html 字符串文本添加到集合中。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 将指定的 html 字符串文本添加到集合中。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 将指定的段落转换为 HTML 并返回为 String 对象。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合实际包含的元素数量。只读 int。

**返回值:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

在集合末尾添加一个 Paragraph。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要添加到集合末尾的 Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

在集合末尾添加 ParagraphCollection 的内容。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要添加到集合末尾的 ParagraphCollection。 |

**返回值:**
int - 添加 Paragraph 的索引位置，如果没有可添加的内容则为 -1。

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

在指定索引处将 Paragraph 插入集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Paragraph 的基于零的索引。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要插入的 Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

在指定索引处将 ParagraphCollection 的内容插入集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入段落的基于零的索引。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要插入的段落。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有元素。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的基于零的索引。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

移除特定段落的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要从集合中移除的段落。 |

**返回值:**
boolean - 如果成功移除项目则为 true；否则为 false。

### addFromHtml(java.lang.String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

将指定的 html 字符串文本添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | HTML 文本。 |

### addFromHtml(java.lang.String text, IExternalResourceResolver resolver, java.lang.String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

将指定的 html 字符串文本添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | HTML 文本。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 解析 URI 并获取引用对象的解析器回调对象。 |
| uri | java.lang.String | 用于添加 HTML 文档的 URI。用于解析相对链接。 |

--------------------
指定 resolver 可能会引入漏洞。请谨慎使用。

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

将指定的段落转换为 HTML 并返回为 String 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstParagraphIndex | int | 第一个段落的索引 int |
| paragraphsCount | int | 段落数量 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 转换选项 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**返回值:**
java.lang.String - 生成的 HTML。