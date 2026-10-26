---
title: ToPdf()
second_title: Aspose.Slides for C++ API संदर्भ
description: Presentation को PDF में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) मेथड

[Presentation](../../../aspose.slides/presentation/) को PDF में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | इनपुट प्रस्तुति का पथ |
| outPath | [System::String](../../../system/string/) | आउटपुट पथ |
## टिप्पणी

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) मेथड

[Presentation](../../../aspose.slides/presentation/) को PDF में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | इनपुट प्रस्तुति का पथ |
| outPath | [System::String](../../../system/string/) | आउटपुट पथ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | आउटपुट PDF विकल्प |
## टिप्पणी

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) मेथड

[Presentation](../../../aspose.slides/presentation/) को PDF में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| outPath | [System::String](../../../system/string/) | आउटपुट पथ |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) मेथड

[Presentation](../../../aspose.slides/presentation/) को PDF में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| outPath | [System::String](../../../system/string/) | आउटपुट पथ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | आउटपुट PDF विकल्प |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Convert](../)
* क्लास [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* नामस्थान [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)