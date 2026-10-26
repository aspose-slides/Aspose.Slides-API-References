---
title: get_AccessPermissions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डॉक्यूमेंट को उपयोगकर्ता एक्सेस के साथ खोलते समय किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल है। देखें PdfAccessPermissions.
type: docs
weight: 300
url: /hi/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() मेथड


डॉक्यूमेंट को उपयोगकर्ता एक्सेस के साथ खोलते समय कौन सी एक्सेस अनुमति प्रदान की जानी चाहिए, यह निर्धारित करने वाले फ़्लैग्स का एक सेट शामिल है। देखें [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## टिप्पणी


```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## देखें

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* क्लास [PdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)