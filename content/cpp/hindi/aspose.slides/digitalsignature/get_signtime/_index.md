---
title: get_SignTime()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "जब दस्तावेज़ पर हस्ताक्षर किया गया था, उसका समय। केवल पढ़ने योग्य System::DateTime."
type: docs
weight: 27
url: /hi/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() विधि

जब दस्तावेज़ पर हस्ताक्षर किए जाने का समय। केवल पढ़ने योग्य [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## देखें

* क्लास [DateTime](../../../system/datetime/)
* क्लास [DigitalSignature](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)