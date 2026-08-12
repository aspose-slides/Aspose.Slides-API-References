---
title: get_SensitivityLabels()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबलों का संग्रह लौटाता है। केवल- पढ़ने योग्य ISensitivityLabelCollection.
type: docs
weight: 391
url: /hi/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() मेथड


वापस देता है प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबलों का संग्रह। केवल-पढ़ने योग्य [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// लागू किए गए लेबल प्रिंट करें
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* क्लास [IPresentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)