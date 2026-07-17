---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。
type: docs
weight: 209
url: /zh/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::String) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |

### 返回值

已添加的幻灯片。

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) 方法

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入的位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |
| useSlideWithIndexAsStart | **bool** | 此标志决定插入的起始方式：从新幻灯片开始或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

### 返回值

已添加的幻灯片。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [String](../../../system/string/)
* 类 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 类 [SlideCollection](../)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)