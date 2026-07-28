---
title: ToPdf()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a Presentation PDF formátumba.
type: docs
weight: 14
url: /hu/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) PDF formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | A bemeneti bemutató útvonala |
| outPath | [System::String](../../../system/string/) | Kimeneti útvonal |
## Megjegyzés




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) PDF formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | A bemeneti bemutató útvonala |
| outPath | [System::String](../../../system/string/) | Kimeneti útvonal |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Kimeneti PDF beállítások |
## Megjegyzés




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) PDF formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Bemeneti bemutató |
| outPath | [System::String](../../../system/string/) | Kimeneti útvonal |
## Megjegyzés




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) PDF formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Bemeneti bemutató |
| outPath | [System::String](../../../system/string/) | Kimeneti útvonal |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Kimeneti PDF beállítások |
## Megjegyzés




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Lásd még

* Típusdef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Convert](../)
* Osztály [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)