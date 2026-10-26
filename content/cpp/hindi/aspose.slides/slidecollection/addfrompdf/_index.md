---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API संदर्भ
description: PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।
type: docs
weight: 183
url: /hi/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) विधि

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF दस्तावेज़ का पथ |

### वापसी मान

जोड़ी गई स्लाइडें
## टिप्पणियाँ



उदाहरण: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) विधि

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें PDF आयात विकल्पों को ध्यान में रखते हुए संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF दस्तावेज़ का पथ |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF आयात के विकल्प |

### वापसी मान

जोड़ी गई स्लाइडें
## टिप्पणियाँ



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) विधि

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF दस्तावेज़ के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम |

### वापसी मान

जोड़ी गई स्लाइडें
## टिप्पणियाँ



उदाहरण: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) विधि

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF दस्तावेज़ के स्रोत के रूप में उपयोग की जाने वाली स्ट्रीम |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF आयात के विकल्प |

### वापसी मान

जोड़ी गई स्लाइडें
## टिप्पणियाँ



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// तालिकाओं का पता लगाना सेट करें
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## देखें भी

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [String](../../../system/string/)
* क्लास [SlideCollection](../)
* क्लास [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)