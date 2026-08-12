---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यह गुण निर्धारित करता है कि Presentation क्लास का एक इंस्टेंस लाइफ़टाइम के दौरान स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है या नहीं। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation की इंस्टेंस लाइफ़टाइम के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:"
type: docs
weight: 1
url: /hi/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() विधि

यह गुण निर्धारित करता है कि क्या [Presentation](../../presentation/) क्लास का एक इंस्टेंस लाइफ़टाइम के दौरान स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी उपभोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को [Presentation](../../presentation/) की इंस्टेंस लाइफ़टाइम के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## टिप्पणियाँ

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException उत्पन्न होगी क्योंकि pres.pptx को Presentation के जीवनकाल के लिए लॉक किया गया है
    // File::Delete(u"pres.pptx");
}
// Presentation ऑब्जेक्ट नष्ट होने के बाद, फ़ाइल अनलॉक हो जाती है और इसे हटाया जा सकता है
IO::File::Delete(u"pres.pptx");
```

## संबंधित देखें

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* क्लास [IBlobManagementOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)