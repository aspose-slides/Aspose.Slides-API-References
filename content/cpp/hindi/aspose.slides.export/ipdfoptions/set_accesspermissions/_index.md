---
title: set_AccessPermissions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़्लैग्स का एक सेट शामिल है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन-सी एक्सेस अनुमतियाँ प्रदान की जानी चाहिए। देखें PdfAccessPermissions.
type: docs
weight: 274
url: /hi/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) method

दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलने पर कौन-सी एक्सेस अनुमति प्रदान की जानी चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल है। देखें [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## टिप्पणियाँ



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## संबंधित देखें

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* क्लास [IPdfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)