---
title: AddFromPdf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।
type: docs
weight: 131
url: /hi/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) मेथड

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF दस्तावेज़ का पथ |

### लौटाया मान

जोड़ी गई स्लाइड्स
## टिप्पणी



उदाहरण: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) मेथड

PDF दस्तावेज़ से स्लाइड बनाता है और pdf इम्पोर्ट विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF दस्तावेज़ का पथ |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | pdf इम्पोर्ट के विकल्प |

### लौटाया मान

जोड़ी गई स्लाइड्स
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) मेथड

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक स्ट्रीम जो PDF दस्तावेज़ स्रोत के रूप में उपयोग किया जाएगा |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | pdf इम्पोर्ट के विकल्प |

### लौटाया मान

जोड़ी गई स्लाइड्स
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// टेबल का पता लगाने के लिए सेट करें
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) मेथड

PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक स्ट्रीम जो PDF दस्तावेज़ स्रोत के रूप में उपयोग किया जाएगा |

### लौटाया मान

जोड़ी गई स्लाइड्स
## टिप्पणी



उदाहरण: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## देखें

* टाइपडेफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [String](../../../system/string/)
* क्लास [ISlideCollection](../)
* क्लास [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)