---
title: set_SlideShowType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "स्लाइड शो प्रकार को सेट करता है। निम्नलिखित SlideShowType पूर्वजों द्वारा दर्शाया गया: BrowsedAtKiosk, PresentedBySpeaker और BrowsedByIndividual"
type: docs
weight: 14
url: /hi/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) विधि


स्लाइड शो प्रकार को सेट करता है। निम्नलिखित [SlideShowType](../../slideshowtype/) पूर्वज: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) और [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>();

// "Browsed at a kiosk (full screen)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Browsed by individual (window)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Presented by a speaker (full screen)" प्रकार सेट करने के लिए
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [SlideShowType](../../slideshowtype/)
* क्लास [SlideShowSettings](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)