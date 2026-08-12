---
title: RemoveWriteProtection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस प्रस्तुति के लिखने की सुरक्षा को हटाता है।
type: docs
weight: 144
url: /hi/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() विधि

इस प्रस्तुति के लिए लिखने की सुरक्षा हटाता है।

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## टिप्पणियाँ

यह नमूना कोड दिखाता है कि आप PowerPoint [Presentation](../../presentation/) से लिखने की सुरक्षा कैसे हटा सकते हैं।

```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [ProtectionManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)