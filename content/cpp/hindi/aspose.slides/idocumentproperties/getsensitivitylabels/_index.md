---
title: GetSensitivityLabels()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कस्टम दस्तावेज़ प्रॉपर्टीज़ से संवेदनशीलता लेबल की एक श्रृंखला प्राप्त करता है (Microsoft Information Protection SDK Metadata)।
type: docs
weight: 872
url: /hi/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() विधि

कस्टम दस्तावेज़ प्रोपर्टीज़ (Microsoft Information Protection SDK Metadata) से संवेदनशीलता लेबल की एक ऐरे प्राप्त करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## टिप्पणियां

निम्नलिखित कोड दर्शाता है कि संवेदनशीलता लेबल जानकारी को कस्टम दस्तावेज़ प्रोपर्टीज़ से आधुनिक SensitivityLabels संग्रह में कैसे स्थानांतरित किया जाए:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// कस्टम दस्तावेज़ प्रॉपर्टीज़ से संवेदनशीलता लेबल प्राप्त करें
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // लेबल को संग्रह में जोड़ें
    // यहाँ आप लेबल जानकारी की वैधता (लेबल उपलब्ध है आदि) की जाँच जोड़ सकते हैं
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISensitivityLabel](../../isensitivitylabel/)
* क्लास [IDocumentProperties](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)