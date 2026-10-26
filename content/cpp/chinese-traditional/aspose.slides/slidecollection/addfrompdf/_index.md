---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API 參考
description: 從 PDF 文件建立幻燈片，並將它們新增至集合的末端。
type: docs
weight: 183
url: /zh-hant/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) 方法


從 PDF 文件建立幻燈片，並將它們新增至集合的末端。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF 文件的路徑 |

### 返回值

已新增幻燈片
## 備註



範例： 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) 方法


在考慮 PDF 匯入選項的情況下，從 PDF 文件建立幻燈片，並將它們新增至集合的末端。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF 文件的路徑 |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF 匯入的選項 |

### 返回值

已新增幻燈片
## 備註



範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) 方法


從 PDF 文件建立幻燈片，並將它們新增至集合的末端。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 PDF 文件來源的資料流 |

### 返回值

已新增幻燈片
## 備註



範例： 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) 方法


從 PDF 文件建立幻燈片，並將它們新增至集合的末端。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用作 PDF 文件來源的資料流 |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF 匯入的選項 |

### 返回值

已新增幻燈片
## 備註



範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// 設定偵測表格
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## 另請參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [String](../../../system/string/)
* 類別 [SlideCollection](../)
* 類別 [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)