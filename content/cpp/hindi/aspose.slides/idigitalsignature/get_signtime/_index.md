---
title: get_SignTime()
second_title: Aspose.Slides for C++ API संदर्भ
description: "दस्तावेज़ पर हस्ताक्षर किए जाने का समय। केवल पढ़ने योग्य System::DateTime."
type: docs
weight: 27
url: /hi/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() मेथड

दस्तावेज़ पर हस्ताक्षर किए जाने का समय। केवल पढ़ने योग्य [System::DateTime](../../../system/datetime/)।

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## संबंधित देखें

* क्लास [DateTime](../../../system/datetime/)
* क्लास [IDigitalSignature](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)