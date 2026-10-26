---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API संदर्भ
description: इसे दर्शाता है कि VBAProject पासवर्ड द्वारा सुरक्षित है या नहीं, ताकि प्रोजेक्ट प्रॉपर्टीज़ देखी जा सकें। केवल-पढ़ने योग्य bool.
type: docs
weight: 40
url: /hi/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() विधि


इसे इंगित करता है कि VBAProject पासवर्ड द्वारा सुरक्षित है या नहीं, जिससे प्रोजेक्ट प्रॉपर्टीज़ देखी जा सकती हैं। केवल-पढ़ने योग्य **bool**।

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## संबंधित देखें

* वर्ग [VbaProject](../)
* नेमस्पेस [Aspose::Slides::Vba](../../)
* लाइब्रेरी [Aspose.Slides](../../../)