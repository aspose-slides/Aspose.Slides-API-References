---
title: ToPdf()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi Presentation ke PDF.
type: docs
weight: 14
url: /id/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metode

Mengonversi [Presentation](../../../aspose.slides/presentation/) ke PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Jalur presentasi masukan |
| outPath | [System::String](../../../system/string/) | Jalur keluaran |
## Catatan

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metode

Mengonversi [Presentation](../../../aspose.slides/presentation/) ke PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Jalur presentasi masukan |
| outPath | [System::String](../../../system/string/) | Jalur keluaran |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opsi PDF keluaran |
## Catatan

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metode

Mengonversi [Presentation](../../../aspose.slides/presentation/) ke PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi masukan |
| outPath | [System::String](../../../system/string/) | Jalur keluaran |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metode

Mengonversi [Presentation](../../../aspose.slides/presentation/) ke PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi masukan |
| outPath | [System::String](../../../system/string/) | Jalur keluaran |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opsi PDF keluaran |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Convert](../)
* Kelas [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Ruang nama [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)