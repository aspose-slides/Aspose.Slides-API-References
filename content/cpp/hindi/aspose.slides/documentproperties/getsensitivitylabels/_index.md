---
title: GetSensitivityLabels()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: कस्टम दस्तावेज़ प्रॉपर्टीज़ (Microsoft Information Protection SDK Metadata) से संवेदनशीलता लेबलों की एक सरणी प्राप्त करता है।
type: docs
weight: 859
url: /hi/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() विधि

कस्टम दस्तावेज़ प्रॉपर्टी (Microsoft Information Protection SDK Metadata) से संवेदनशीलता लेबलों की एक ऐरे प्राप्त करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## टिप्पणी

निम्नलिखित कोड दिखाता है कि कस्टम दस्तावेज़ प्रॉपर्टी से संवेदनशीलता लेबल जानकारी को आधुनिक SensitivityLabels संग्रह में कैसे ले जाएँ:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// कस्टम दस्तावेज़ प्रॉपर्टीज़ से संवेदनशीलता लेबल प्राप्त करें
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // संग्रह में लेबल जोड़ें
    // यहाँ आप लेबल जानकारी की वैधता (लेबल उपलब्ध है आदि) के लिए जांच जोड़ सकते हैं
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISensitivityLabel](../../isensitivitylabel/)
* क्लास [DocumentProperties](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)