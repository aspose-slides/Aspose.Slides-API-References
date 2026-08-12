---
title: get_Password()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "पासवर्ड प्राप्त करता है। पढ़ें System::String."
type: docs
weight: 105
url: /hi/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() विधि

पासवर्ड प्राप्त करता है। पढ़ें [System::String](../../../system/string/)।

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## टिप्पणियाँ

पासवर्ड।

निम्नलिखित नमूना कोड दिखाता है कि पासवर्ड-संरक्षित PowerPoint [Presentation](../../presentation/) को कैसे खोलें।
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [LoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)