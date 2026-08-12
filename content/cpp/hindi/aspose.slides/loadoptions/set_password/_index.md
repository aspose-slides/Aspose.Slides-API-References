---
title: set_Password()
second_title: Aspose.Slides for C++ API संदर्भ
description: "पासवर्ड सेट करता है। लिखें System::String."
type: docs
weight: 118
url: /hi/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) मेथड

पासवर्ड सेट करता है। लिखें [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## टिप्पणियां

पासवर्ड। 

निम्नलिखित नमूना कोड दिखाता है कि पासवर्ड सुरक्षित PowerPoint [Presentation](../../presentation/) को कैसे खोलें। 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)