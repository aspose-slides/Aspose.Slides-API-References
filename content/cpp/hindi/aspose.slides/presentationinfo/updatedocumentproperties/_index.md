---
title: UpdateDocumentProperties()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बाइंडेड प्रस्तुति की प्रॉपर्टीज़ को अपडेट करता है।
type: docs
weight: 92
url: /hi/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) विधि

बाइंडेड प्रस्तुति की प्रॉपर्टीज़ को अपडेट करता है।

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## टिप्पणी

यह उदाहरण दिखाता है कि कैसे [PresentationInfo::UpdateDocumentProperties](./) विधि को कॉल करके दस्तावेज़ प्रॉपर्टीज़ को अपडेट किया जाए जो [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) विधि के कॉल द्वारा लौटाए गए हैं।

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IDocumentProperties](../../idocumentproperties/)
* क्लास [PresentationInfo](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)