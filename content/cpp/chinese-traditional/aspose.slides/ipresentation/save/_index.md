---
title: Save()
second_title: Aspose.Slides for C++ API 參考文件
description: 將簡報的所有投影片儲存為具有指定格式的檔案。
type: docs
weight: 404
url: /zh-hant/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) 方法

將簡報的所有投影片儲存為具有指定格式的檔案。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 已建立檔案的路徑。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) 方法

將簡報的所有投影片儲存至指定格式的串流中。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸出串流。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 方法

將簡報的所有投影片儲存為具有指定格式且帶有其他選項的檔案。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 已建立檔案的路徑。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 其他格式選項。 |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 方法

將簡報的所有投影片儲存至指定格式且帶有其他選項的串流中。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸出串流。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 其他格式選項。 |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) 方法

將簡報的特定投影片儲存為具有指定格式的檔案。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 已建立檔案的路徑。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 投影片位置的陣列，起始值為 1。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 方法

將簡報的特定投影片儲存為具有指定格式的檔案。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 已建立檔案的路徑。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 投影片位置的陣列，起始值為 1。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 其他格式選項。 |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) 方法

將簡報的特定投影片儲存至指定格式的串流中。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸出串流。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 投影片位置的陣列，起始值為 1。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 方法

將簡報的特定投影片儲存至指定格式的串流中。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸出串流。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 投影片位置的陣列，起始值為 1。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 匯出資料的格式。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 其他格式選項。 |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) 方法

將簡報的所有投影片儲存為一組表示 XAML 標記的檔案。

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | XAML 格式的選項。 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## 參見

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [IPresentation](../)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* 類別 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)