---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह दर्शाता है कि VBAProject को प्रोजेक्ट गुण देखने के लिए पासवर्ड द्वारा संरक्षित किया गया है। केवल पढ़ने योग्य bool.
type: docs
weight: 40
url: /hi/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() मेथड


यह संकेत देता है कि VBAProject को पासवर्ड द्वारा संरक्षित किया गया है ताकि प्रोजेक्ट गुण देखे जा सकें। केवल पढ़ने योग्य **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## देखें

* क्लास [IVbaProject](../)
* नामस्थान [Aspose::Slides::Vba](../../)
* लाइब्रेरी [Aspose.Slides](../../../)