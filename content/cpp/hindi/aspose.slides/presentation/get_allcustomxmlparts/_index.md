---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन में सभी कस्टम डेटा भाग लौटाता है। केवल-पढ़ने योग्य ICustomXmlPart[].
type: docs
weight: 287
url: /hi/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() मेथड

प्रेजेंटेशन में सभी कस्टम डेटा भाग लौटाता है। केवल-पढ़ने योग्य [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## टिप्पणियाँ

निम्नलिखित उदाहरण दर्शाते हैं कि PowerPoint [Presentation](../) से सभी कस्टम XML भाग कैसे साफ़ किए जाएँ। 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ICustomXmlPart](../../icustomxmlpart/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)