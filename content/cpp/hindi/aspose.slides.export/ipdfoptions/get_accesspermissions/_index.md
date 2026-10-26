---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़्लैग्स का एक सेट शामिल करता है जो यह निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलते समय किन पहुँच अनुमतियों को प्रदान किया जाना चाहिए। देखें PdfAccessPermissions.
type: docs
weight: 261
url: /hi/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() विधि

फ़्लैग्स का एक सेट शामिल करता है जो यह निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलते समय किन पहुँच अनुमतियों को प्रदान किया जाना चाहिए। देखें [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* क्लास [IPdfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)