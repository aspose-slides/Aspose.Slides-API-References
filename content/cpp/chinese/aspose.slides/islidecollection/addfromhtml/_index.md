---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 从 HTML 文本创建幻灯片并将其添加到集合的末尾。
type: docs
weight: 144
url: /zh/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要添加的 Html。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::AddFromHtml(System::String) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要添加的 Html。 |

### 返回值

已添加的幻灯片

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |

### 返回值

已添加的幻灯片

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加的幻灯片。

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |

### 返回值

已添加的幻灯片

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [String](../../../system/string/)
* 类 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 类 [ISlideCollection](../)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)