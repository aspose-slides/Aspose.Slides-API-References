---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API संदर्भ
description: बाइंडेड प्रेज़ेंटेशन के गुण अपडेट करता है।
type: docs
weight: 92
url: /hi/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) मेथड


बाइंडेड प्रेजेंटेशन के गुण अद्यतन करता है।

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | डॉक्यूमेंट गुण [IDocumentProperties](../../idocumentproperties/) |
## टिप्पणी



यह उदाहरण दिखाता है कि कैसे [IPresentationInfo::UpdateDocumentProperties](./) मेथड को कॉल किया जाए ताकि [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) मेथड के कॉल द्वारा लौटाए गए डॉक्यूमेंट गुणों को अपडेट किया जा सके। 
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
* क्लास [IPresentationInfo](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)