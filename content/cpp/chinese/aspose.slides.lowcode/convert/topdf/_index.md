---
title: ToPdf()
second_title: Aspose.Slides C++ API 参考
description: 将 Presentation 转换为 PDF。
type: docs
weight: 14
url: /zh/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 输入演示文稿的路径 |
| outPath | [System::String](../../../system/string/) | 输出路径 |
## 备注

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 输入演示文稿的路径 |
| outPath | [System::String](../../../system/string/) | 输出路径 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 输出 PDF 选项 |
## 备注

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入演示文稿 |
| outPath | [System::String](../../../system/string/) | 输出路径 |
## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 PDF。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入演示文稿 |
| outPath | [System::String](../../../system/string/) | 输出路径 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 输出 PDF 选项 |
## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Convert](../)
* 类 [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)