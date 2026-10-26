---
title: ToPdf()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu PDF'ye dönüştürür.
type: docs
weight: 14
url: /tr/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metodu


[Presentation](../../../aspose.slides/presentation/) öğesini PDF'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Giriş sunumunun yolu |
| outPath | [System::String](../../../system/string/) | Çıktı yolu |
## Açıklamalar




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metodu


[Presentation](../../../aspose.slides/presentation/) öğesini PDF'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Giriş sunumunun yolu |
| outPath | [System::String](../../../system/string/) | Çıktı yolu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Çıktı PDF seçenekleri |
## Açıklamalar 




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metodu


[Presentation](../../../aspose.slides/presentation/) öğesini PDF'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| outPath | [System::String](../../../system/string/) | Çıktı yolu |
## Açıklamalar 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metodu


[Presentation](../../../aspose.slides/presentation/) öğesini PDF'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| outPath | [System::String](../../../system/string/) | Çıktı yolu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Çıktı PDF seçenekleri |
## Açıklamalar 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Convert](../)
* Sınıf [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* İsim Alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)