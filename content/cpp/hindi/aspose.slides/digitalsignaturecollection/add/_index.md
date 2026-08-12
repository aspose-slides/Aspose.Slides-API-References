---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: कलेक्शन के अंत में हस्ताक्षर जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) मेथड

कलेक्शन के अंत में हस्ताक्षर जोड़ता है।

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | जोड़ने के लिए Signature। |
## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IDigitalSignature](../../idigitalsignature/)
* क्लास [DigitalSignatureCollection](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)