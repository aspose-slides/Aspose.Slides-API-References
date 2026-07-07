---
title: InsertFromHtml
second_title: Aspose.Sildes for .NET API 參考
description: 從 HTML 文字建立投影片，並將其插入至指定位置的集合中。
type: docs
weight: 140
url: /zh-hant/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlText | String | 要加入的 HTML。 |
| resolver | IExternalResourceResolver | 用於擷取外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | String | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

### 另請參閱

* 介面 [ISlide](../../islide)
* 介面 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlText | String | 要加入的 HTML。 |
| resolver | IExternalResourceResolver | 用於擷取外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | Boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。如果 **false**，則資料將加入已建立的投影片中。 |

### 返回值

已加入的投影片。

### 另請參閱

* 介面 [ISlide](../../islide)
* 介面 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlText | String | 要加入的 HTML。 |

### 返回值

已加入的投影片

### 另請參閱

* 介面 [ISlide](../../islide)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlText | String | 要加入的 HTML。 |
| useSlideWithIndexAsStart | Boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。如果 **false**，則資料將加入已建立的投影片中。 |

### 返回值

已加入的投影片

### 另請參閱

* 介面 [ISlide](../../islide)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlReader | TextReader | 將用作 HTML 檔案來源的 TextReader 物件。 |
| resolver | IExternalResourceResolver | 用於擷取外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | String | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

### 另請參閱

* 介面 [ISlide](../../islide)
* 介面 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlReader | TextReader | 將用作 HTML 檔案來源的 TextReader 物件。 |

### 返回值

已加入的投影片

### 另請參閱

* 介面 [ISlide](../../islide)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlStream | Stream | 將用作 HTML 檔案來源的 Stream 物件。 |
| resolver | IExternalResourceResolver | 用於擷取外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | String | 指定 HTML 的 URI。用於解析相對連結。 |

### 返回值

已加入的投影片。

### 另請參閱

* 介面 [ISlide](../../islide)
* 介面 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlStream | Stream | 將用作 HTML 檔案來源的 Stream 物件。 |
| resolver | IExternalResourceResolver | 用於擷取外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | Boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。如果 **false**，則資料將加入已建立的投影片中。 |

### 返回值

已加入的投影片。

### 另請參閱

* 介面 [ISlide](../../islide)
* 介面 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlStream | Stream | 將用作 HTML 檔案來源的 Stream 物件。 |

### 返回值

已加入的投影片

### 另請參閱

* 介面 [ISlide](../../islide)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

自 HTML 文字建立投影片，並將其插入至指定位置的集合中。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | Int32 | 要插入的位置。 |
| htmlStream | Stream | 將用作 HTML 檔案來源的 Stream 物件。 |
| useSlideWithIndexAsStart | Boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。如果 **false**，則資料將加入已建立的投影片中。 |

### 返回值

已加入的投影片

### 另請參閱

* 介面 [ISlide](../../islide)
* 類別 [SlideCollection](../../slidecollection)
* 命名空間 [Aspose.Slides](../../slidecollection)
* 組件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->