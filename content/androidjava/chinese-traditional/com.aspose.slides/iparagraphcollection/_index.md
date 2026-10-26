---
title: IParagraphCollection
second_title: Aspose.Slides for Android Java API 參考
description: 表示一個段落的集合。
type: docs
url: /zh-hant/com.aspose.slides/iparagraphcollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

表示一個段落的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合實際包含的元素數量。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 將 Paragraph 新增至集合的末端。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 將 ParagraphCollection 的內容新增至集合的末端。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 在指定索引處將 Paragraph 插入集合。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 在指定索引處將 ParagraphCollection 的內容插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 移除特定段落的第一次出現。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 將指定 HTML 字串的文字新增至集合。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 將指定 HTML 字串的文字新增至集合。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 將指定的段落轉換為 HTML，並以 String 物件返回。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


取得指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合實際包含的元素數量。唯讀 int.

**返回值：**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


將 Paragraph 新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要新增至集合末端的 Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


將 ParagraphCollection 的內容新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要新增至集合末端的 ParagraphCollection。 |

**返回值：**
int - Paragraph 被新增的索引，若沒有任何可新增則為 -1。
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


在指定索引處將 Paragraph 插入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | Paragraph 應被插入的零基索引。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要插入的 Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


在指定索引處將 ParagraphCollection 的內容插入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 段落應被插入的零基索引。 |
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


移除特定段落的第一次出現。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要從集合中移除的段落。 |

**返回值：**
boolean - 若成功移除項目則為 true；否則為 false。
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


將指定 HTML 字串的文字新增至集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


將指定 HTML 字串的文字新增至集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 解析 URI 並取得參照物件的解析器回呼物件。 |
| uri | java.lang.String | 用於加入 HTML 文件的 URI。用於解析相對連結。 |

--------------------
指定解析器可能會引入安全漏洞。請謹慎使用。 |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


將指定的段落轉換為 HTML，並以 String 物件返回。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstParagraphIndex | int | 第一段落的索引 int |
| paragraphsCount | int | 段落數量 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 轉換選項 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**返回值：**
java.lang.String - 產生的 HTML。