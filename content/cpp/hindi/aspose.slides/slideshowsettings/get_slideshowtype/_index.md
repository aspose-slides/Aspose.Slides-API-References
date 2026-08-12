---
title: get_SlideShowType()
second_title: Aspose.Slides for C++ API संदर्भ
description: "स्लाइड शो प्रकार प्राप्त करता है। निम्नलिखित SlideShowType पूर्वज द्वारा प्रतिनिधित्व किया गया: BrowsedAtKiosk, PresentedBySpeaker और BrowsedByIndividual"
type: docs
weight: 1
url: /hi/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() विधि

स्लाइड शो प्रकार प्राप्त करता है। निम्नलिखित [SlideShowType](../../slideshowtype/) पूर्वज द्वारा प्रतिनिधित्व किया गया: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) और [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>();

// "कियोस्क पर ब्राउज़ किया गया (पूर्ण स्क्रीन)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "व्यक्ति द्वारा ब्राउज़ किया गया (विंडो)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "वक्ता द्वारा प्रस्तुत किया गया (पूर्ण स्क्रीन)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [SlideShowType](../../slideshowtype/)
* क्लास [SlideShowSettings](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)