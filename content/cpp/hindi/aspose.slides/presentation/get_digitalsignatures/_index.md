---
title: get_DigitalSignatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेज़ेंटेशन पर हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य IDigitalSignatureCollection.
type: docs
weight: 261
url: /hi/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() विधि

प्रेज़ेंटेशन पर हस्ताक्षर करने के लिये प्रयुक्त हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;

    System::Console::WriteLine(u"Signatures used to sign the presentation: ");

    for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
    {
        auto signature = pres->get_DigitalSignatures()->idx_get(i);
        System::Console::WriteLine(u"{0}, {1} --- {2}",
            signature->get_Certificate()->get_SubjectName()->get_Name(),
            signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm"),
            (signature->get_IsValid() ? u"VALID" : u"INVALID")
        );
        allSignaturesAreValid &= signature->get_IsValid();
    }
}
@verbatim 
if (allSignaturesAreValid)
    System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
else
    System::Console::WriteLine(u"Presentation has been modified since signing.");
@endverbatim }
```

## इसे भी देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)