---
title: get_IsValid()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि यह डिजिटल सिग्नेचर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं की गई है, तो यह मान सत्य होगा। केवल-पढ़ने योग्य bool.
type: docs
weight: 14
url: /hi/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() विधि


यदि यह डिजिटल सिग्नेचर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं की गई है, तो यह मान सत्य होगा। केवल-पढ़ने योग्य **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## टिप्पणियाँ


```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## संबंधित देखें

* क्लास [DigitalSignature](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)