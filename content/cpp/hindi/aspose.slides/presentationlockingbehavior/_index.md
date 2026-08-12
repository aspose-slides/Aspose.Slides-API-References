---
title: PresentationLockingBehavior
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "IPresentation स्रोत (फ़ाइल या System::IO::Stream) को लोड करने और IPPresentation के एक उदाहरण के साथ काम करते समय व्यवहार को दर्शाता है।"
type: docs
weight: 6748
url: /hi/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

स्रोत [IPresentation](../ipresentation/) (फ़ाइल या [System::IO::Stream](../../system.io/stream/)) को लोड करने और [IPresentation](../ipresentation/) के एक उदाहरण के साथ काम करते समय उसके व्यवहार को दर्शाता है।

```cpp
enum class PresentationLockingBehavior
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| LoadAndRelease | 0 | स्रोत केवल [IPresentation](../ipresentation/) कंस्ट्रक्टर निष्पादन के समय के लिए लॉक किया जाएगा। |
| KeepLocked | 1 | स्रोत [IPresentation](../ipresentation/) उदाहरण के पूरे जीवनकाल के लिए लॉक रहेगा, जब तक इसे नष्ट नहीं किया जाता। |

## टिप्पणी

स्रोत वह पैरामीटर है जो [IPresentation](../ipresentation/) कंस्ट्रक्टर को पास किया जाता है। नीचे दिए गये उदाहरण में, स्रोत "pres.pptx" फ़ाइल है:

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

इस उदाहरण में, स्रोत ("pres.pptx" फ़ाइल) [IPresentation](../ipresentation/) उदाहरण के जीवनकाल के लिए लॉक रहेगा, अर्थात इसे अन्य प्रक्रिया द्वारा बदला या हटाया नहीं जा सकता।

## देखें

* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)