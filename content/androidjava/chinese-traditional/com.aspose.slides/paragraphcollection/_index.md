---
title: ParagraphCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示段落的集合。
type: docs
url: /zh-hant/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

表示段落的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | 在集合尾端加入一個 Paragraph。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | 在集合尾端加入 ParagraphCollection 的內容。 |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | 確定 List 中特定項目的索引。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 在指定索引處將 Paragraph 插入集合。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 在指定索引處將 ParagraphCollection 的內容插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | 將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製至陣列，從特定的陣列索引開始。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一個出現的特定物件。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [getSlide()](#getSlide--) | 傳回段落集合的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回段落集合的父簡報。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 將指定的 HTML 字串文字加入集合。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 將指定的 HTML 字串文字加入集合。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 將指定的段落轉換為 HTML，並以 String 物件返回。 |

### getCount() {#getCount--}
```
public final int getCount()
```

取得集合中實際包含的元素數量。唯讀 int。

**返回:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。唯讀 boolean。

**返回:**
boolean - 若 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則為 true；否則為 false。

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

在集合尾端加入一個 Paragraph。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要加入集合尾端的 Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

在集合尾端加入 ParagraphCollection 的內容。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要加入集合尾端的 ParagraphCollection。 |

**返回:**
int - Paragraph 被加入的索引；若沒有可加入的項目則為 -1。

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

確定 List 中特定項目的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要在 List 中定位的物件。 |

**返回:**
int - 若在清單中找到該項目則返回其索引；否則返回 -1。

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

在指定索引處將 Paragraph 插入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 Paragraph 的零基索引。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 要插入的 Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

在指定索引處將 ParagraphCollection 的內容插入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入段落的零基索引。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 要插入的段落。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有元素。

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**返回:**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則為 true；否則為 false。

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製至陣列，從特定的陣列索引開始。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製元素的目標一維陣列。陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始的陣列零基索引。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一個出現的特定物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**返回:**
boolean - 若成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除項目則為 true；若未在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目，亦返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

傳回可遍歷集合的列舉器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - 整個集合的 java.util.Iterator。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回段落集合的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回段落集合的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

將指定的 HTML 字串文字加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

將指定的 HTML 字串文字加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | HTML 文字。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 解析 URI 並取得引用物件的回呼 Resolver 物件。 |
| uri | java.lang.String | 用於加入 HTML 文件的 URI。用於解析相對連結。 |

--------------------

指定 resolver 可能會導致漏洞。使用時請謹慎。 |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

將指定的段落轉換為 HTML，並以 String 物件返回。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstParagraphIndex | int | 第一段落索引 int |
| paragraphsCount | int | 段落計數 int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 轉換選項 [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**返回:**
java.lang.String - 生成的 HTML。