---
title: SetWriteProtection()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करें।
type: docs
weight: 131
url: /hi/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) मेथड

निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करें।

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | पासवर्ड। |
## टिप्पणियां

निम्नलिखित नमूना कोड दर्शाता है कि प्रस्तुति पर लिखने की सुरक्षा कैसे सेट करें। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [ProtectionManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)