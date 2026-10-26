---
title: ParagraphCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示一个段落集合。
type: docs
url: /zh/com.aspose.slides/paragraphcollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

表示段落集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取集合中实际包含的元素数量。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 将 Paragraph 添加到集合的末尾。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 将 ParagraphCollection 的内容添加到集合的末尾。 |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | 确定 List 中特定项的索引。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 在指定索引处将 Paragraph 插入集合。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 在指定索引处将 ParagraphCollection 的内容插入集合。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从指定的数组索引开始。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getSlide()](#getSlide--) | 返回段落集合的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回段落集合的父演示文稿。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 将指定 HTML 字符串的文本添加到集合中。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 将指定 HTML 字符串的文本添加到集合中。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 将指定段落转换为 HTML 并返回为 String 对象。 |

### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。只读 boolean。

**返回值:**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

将 Paragraph 添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要添加到集合末尾的 Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

将 ParagraphCollection 的内容添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要添加到集合末尾的 ParagraphCollection。 |

**返回值:**
int - 已添加 Paragraph 的索引，若没有可添加的内容则为 -1。

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

确定 List 中特定项的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要在 List 中定位的对象。 |

**返回值:**
int - 若在列表中找到 item，则返回其索引；否则返回 -1。

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

在指定索引处将 Paragraph 插入集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Paragraph 的基于零的索引。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要插入的 Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

在指定索引处将 ParagraphCollection 的内容插入集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入段落的基于零的索引。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要插入的段落。 |

### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有元素。

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回值:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 则为 true；否则为 false。

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从指定的数组索引开始。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | 目标为一维数组，用于接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素。数组必须使用基于零的索引。 |
| arrayIndex | int | 复制开始时数组的基于零的索引。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的基于零的索引。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的对象。 |

**返回值:**
boolean - 如果成功从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 则为 true；否则为 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，此方法也返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

返回一个遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - 整个集合的 java.util.Iterator。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回段落集合的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回段落集合的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

将指定 HTML 字符串的文本添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | HTML 文本。 |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

将指定 HTML 字符串的文本添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | HTML 文本。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 解决 URI 并获取引用对象的解析器回调对象。 |
| uri | java.lang.String | 用于添加 HTML 文档的 URI。用于解析相对链接。 |

指定 resolver 可能会引入漏洞。使用时需谨慎。

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

将指定段落转换为 HTML 并返回为 String 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstParagraphIndex | int | 第一个段落的索引 int |
| paragraphsCount | int | 段落数量 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 转换选项 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**返回值:**
java.lang.String - 生成的 HTML。