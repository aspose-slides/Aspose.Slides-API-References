---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यह प्रॉपर्टी यह निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation के इंस्टेंस के जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:"
type: docs
weight: 14
url: /hi/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) मेथड

यह प्रॉपर्टी यह निर्धारित करती है कि क्या [Presentation](../../presentation/) क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को [Presentation](../../presentation/) के इंस्टेंस के जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## टिप्पणियाँ

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException फेंका जाएगा क्योंकि pres.pptx को Presentation के जीवनकाल के लिए लॉक किया गया है
    // File::Delete(u"pres.pptx");
}
// after Presentation object destroyed, file is unlocked and can be deleted
IO::File::Delete(u"pres.pptx");
```

## देखें

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* क्लास [IBlobManagementOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)