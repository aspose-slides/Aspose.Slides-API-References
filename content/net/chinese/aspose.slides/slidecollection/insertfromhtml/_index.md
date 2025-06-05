---
title: InsertFromHtml
second_title: Aspose.Slides for .NET API Reference
description: 从HTML文本创建幻灯片并将其插入到指定位置的集合中。
type: docs
weight: 140
url: /zh/aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlText | String | 要添加的HTML。 |
| resolver | IExternalResourceResolver | 用于获取外部对象的回调对象。如果此参数为null，则所有外部对象将被忽略。 |
| uri | String | 指定HTML的URI。用于解析相对链接。 |

### 返回值

添加的幻灯片。

### 另请参见

* 接口 [ISlide](../../islide)
* 接口 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlText | String | 要添加的HTML。 |
| resolver | IExternalResourceResolver | 用于获取外部对象的回调对象。如果此参数为null，则所有外部对象将被忽略。 |
| uri | String | 指定HTML的URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | Boolean | 此标志决定如何开始插入：从新幻灯片开始还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上一个空白区域开始。如果 **false**，则数据将添加到创建的幻灯片中。 |

### 返回值

添加的幻灯片。

### 另请参见

* 接口 [ISlide](../../islide)
* 接口 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlText | String | 要添加的HTML。 |

### 返回值

添加的幻灯片

### 另请参见

* 接口 [ISlide](../../islide)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlText | String | 要添加的HTML。 |
| useSlideWithIndexAsStart | Boolean | 此标志决定如何开始插入：从新幻灯片开始还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上一个空白区域开始。如果 **false**，则数据将添加到创建的幻灯片中。 |

### 返回值

添加的幻灯片

### 另请参见

* 接口 [ISlide](../../islide)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlReader | TextReader | 将用作HTML文件源的TextReader对象。 |
| resolver | IExternalResourceResolver | 用于获取外部对象的回调对象。如果此参数为null，则所有外部对象将被忽略。 |
| uri | String | 指定HTML的URI。用于解析相对链接。 |

### 返回值

添加的幻灯片。

### 另请参见

* 接口 [ISlide](../../islide)
* 接口 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlReader | TextReader | 将用作HTML文件源的TextReader对象。 |

### 返回值

添加的幻灯片

### 另请参见

* 接口 [ISlide](../../islide)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlStream | Stream | 将用作HTML文件源的Stream对象。 |
| resolver | IExternalResourceResolver | 用于获取外部对象的回调对象。如果此参数为null，则所有外部对象将被忽略。 |
| uri | String | 指定HTML的URI。用于解析相对链接。 |

### 返回值

添加的幻灯片。

### 另请参见

* 接口 [ISlide](../../islide)
* 接口 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlStream | Stream | 将用作HTML文件源的Stream对象。 |
| resolver | IExternalResourceResolver | 用于获取外部对象的回调对象。如果此参数为null，则所有外部对象将被忽略。 |
| uri | String | 指定HTML的URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | Boolean | 此标志决定如何开始插入：从新幻灯片开始还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上一个空白区域开始。如果 **false**，则数据将添加到创建的幻灯片中。 |

### 返回值

添加的幻灯片。

### 另请参见

* 接口 [ISlide](../../islide)
* 接口 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlStream | Stream | 将用作HTML文件源的Stream对象。 |

### 返回值

添加的幻灯片

### 另请参见

* 接口 [ISlide](../../islide)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

从HTML文本创建幻灯片并将其插入到指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入位置。 |
| htmlStream | Stream | 将用作HTML文件源的Stream对象。 |
| useSlideWithIndexAsStart | Boolean | 此标志决定如何开始插入：从新幻灯片开始还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上一个空白区域开始。如果 **false**，则数据将添加到创建的幻灯片中。 |

### 返回值

添加的幻灯片

### 另请参见

* 接口 [ISlide](../../islide)
* 类 [SlideCollection](../../slidecollection)
* 命名空间 [Aspose.Slides](../../slidecollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->