---
title: Add()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: संग्रह के अंत में हस्ताक्षर जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) मेथड


संग्रह के अंत में हस्ताक्षर जोड़ता है।

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | जोड़ने के लिए हस्ताक्षर। |
## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDigitalSignature](../../idigitalsignature/)
* क्लास [IDigitalSignatureCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)