---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。
type: docs
weight: 157
url: /zh/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |

### 返回值

已添加的幻灯片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件来源的 TextReader 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件来源的 TextReader 对象。 |

### 返回值

已添加的幻灯片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件来源的 Stream 对象。 |

### 返回值

已添加的幻灯片

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到已创建的幻灯片中。 |

### 返回值

已添加的幻灯片

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到已创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件来源的 Stream 对象。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到已创建的幻灯片中。 |

### 返回值

已添加的幻灯片

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到已创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [String](../../../system/string/)
* 类 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 类 [ISlideCollection](../)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)