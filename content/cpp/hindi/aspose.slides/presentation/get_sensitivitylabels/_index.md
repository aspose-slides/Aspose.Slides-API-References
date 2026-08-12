---
title: get_SensitivityLabels()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पढ़ने योग्य ISensitivityLabelCollection.
type: docs
weight: 378
url: /hi/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() मेथड

प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// लागू किए गए लेबल्स प्रिंट करें
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// नया लेबल जोड़ें
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// नीति से संवेदनशीलता लेबल Id प्राप्त करें
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// नीति से Azure AD साइट पहचानकर्ता प्राप्त करें
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)