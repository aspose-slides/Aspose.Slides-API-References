---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 从 HTML 文本创建幻灯片并将其添加到集合的末尾。
type: docs
weight: 196
url: /zh/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加幻灯片。

## SlideCollection::AddFromHtml(System::String) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 要添加的 HTML。 |

### 返回值

已添加幻灯片

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加幻灯片。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | 将用作 HTML 文件源的 TextReader 对象。 |

### 返回值

已添加幻灯片

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | [System::String](../../../system/string/) | 指定 HTML 的 URI。用于解析相对链接。 |

### 返回值

已添加幻灯片。

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

创建幻灯片并将其添加到集合末尾。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 将用作 HTML 文件源的 Stream 对象。 |

### 返回值

已添加幻灯片
## 备注

```cpp
// 创建 Presentation 类的实例。
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // 调用 AddFromHtml 方法并传递 HTML 文件。
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// 使用 Save 方法将文件保存为 PowerPoint 文档。
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)