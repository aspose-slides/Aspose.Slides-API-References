---
title: ToPdf()
second_title: Aspose.Slides for C++ API 參考
description: 將 Presentation 轉換為 PDF。
type: docs
weight: 14
url: /zh-hant/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 輸入簡報的路徑 |
| outPath | [System::String](../../../system/string/) | 輸出路徑 |
## 備註

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 輸入簡報的路徑 |
| outPath | [System::String](../../../system/string/) | 輸出路徑 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 輸出 PDF 選項 |
## 備註

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入簡報 |
| outPath | [System::String](../../../system/string/) | 輸出路徑 |
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入簡報 |
| outPath | [System::String](../../../system/string/) | 輸出路徑 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 輸出 PDF 選項 |
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Convert](../)
* 類別 [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)