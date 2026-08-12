---
title: set_AccessPermissions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्धारित करने वाले फ़्लैग्स का एक सेट शामिल है। देखें PdfAccessPermissions.
type: docs
weight: 313
url: /hi/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) विधि

दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल है। देखें [PdfAccessPermissions](../../pdfaccesspermissions/)।

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## टिप्पणियाँ



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
* लाइब्रेरी [Aspose.Slides](../../../)