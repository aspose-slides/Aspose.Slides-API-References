---
title: IParagraphCollection
second_title: Aspose.Slides 的 Java API 參考
description: 表示段落的集合。
type: docs
url: /zh-hant/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

表示段落的集合。
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 在集合末端加入 Paragraph。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 在集合末端加入 ParagraphCollection 的內容。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 在指定索引處將 Paragraph 插入集合。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 在指定索引處將 ParagraphCollection 的內容插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 移除特定段落的第一次出現。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 將指定的 HTML 字串文字加入集合。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 將指定的 HTML 字串文字加入集合。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 將指定的段落轉換成 HTML，並以 String 物件回傳。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


取得指定索引處的元素。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**回傳值:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合中實際包含的元素數量。唯讀 int。

**回傳值:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


在集合末端加入 Paragraph。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要加入集合末端的 Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


在集合末端加入 ParagraphCollection 的內容。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要加入集合末端的 ParagraphCollection。 |

**回傳值:**
int - 新增 Paragraph 的索引，若沒有可加入的項目則為 -1。
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


在指定索引處將 Paragraph 插入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 Paragraph 的零基索引。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要插入的 Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


在指定索引處將 ParagraphCollection 的內容插入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入段落的零基索引。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要插入的段落。 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引處的元素。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


移除特定段落的第一次出現。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要從集合中移除的段落。 |

**回傳值:**
boolean - 若成功刪除項目則為 true；否則為 false。
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


將指定的 HTML 字串文字加入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


將指定的 HTML 字串文字加入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 解析 URI 並取得參照物件的回呼物件。 |
| uri | java.lang.String | 用於加入 HTML 文件的 URI。用於解析相對連結。

--------------------

指定 resolver 可能會引入安全漏洞。請謹慎使用。 |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


將指定的段落轉換成 HTML，並以 String 物件回傳。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | 第一段落索引 int |
| paragraphsCount | int | 段落數量 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 轉換選項 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**回傳值:**
java.lang.String - 產生的 HTML。