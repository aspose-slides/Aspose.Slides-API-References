---
title: ToPdf()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลง Presentation เป็น PDF.
type: docs
weight: 14
url: /th/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) เมธอด

แปลง [Presentation](../../../aspose.slides/presentation/) เป็น PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | เส้นทางของการนำเสนออินพุต |
| outPath | [System::String](../../../system/string/) | เส้นทางเอาต์พุต |
## หมายเหตุ




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) เมธอด

แปลง [Presentation](../../../aspose.slides/presentation/) เป็น PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | เส้นทางของการนำเสนออินพุต |
| outPath | [System::String](../../../system/string/) | เส้นทางเอาต์พุต |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | ตัวเลือก PDF เอาต์พุต |
## หมายเหตุ




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) เมธอด

แปลง [Presentation](../../../aspose.slides/presentation/) เป็น PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | การนำเสนออินพุต |
| outPath | [System::String](../../../system/string/) | เส้นทางเอาต์พุต |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) เมธอด

แปลง [Presentation](../../../aspose.slides/presentation/) เป็น PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | การนำเสนออินพุต |
| outPath | [System::String](../../../system/string/) | เส้นทางเอาต์พุต |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | ตัวเลือก PDF เอาต์พุต |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## ดูเพิ่มเติม

* การพิมพ์นิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Convert](../)
* คลาส [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)